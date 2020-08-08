# BASH HELPERS

## Installation

### Composer
```bash
composer require marcmascort/bash-helpers
```

### NPM
```bash
npm install mmb-bash-helpers
```

## Functions

Usage is very simply, you only need import helpers file.
```bash
source path/to/helpers
```

### Display

```bash
success <message>
warning <message>
error <message>
highlight <message>
text <message>
title <message>
yell <message>
```

### Execution

```bash
try <command>
die <message>
```

### Files

```bash
make_executable <path/to/fileOrFolder>
make_writable <path/to/fileOrFolder>
make_readable <path/to/fileOrFolder>
make_chmod <modes> <path/to/fileOrFolder>
make_mkdir <path/to/fileOrFolder>
make_mv <path/to/source/fileOrFolder> <path/to/target/fileOrFolder>
make_cp <path/to/source/fileOrFolder> <path/to/target/fileOrFolder>
make_rm <path/to/fileOrFolder>
```

### Strings

```bash
str_replace <search> <replace> <subject>
```

## Libraries

### Certificate generator

```bash
lib/cert-generate <hostname> <folder> <openssl_config_file>
```

### Docker machine port forwarder

```bash
lib/docker-machine-port-forwarder <port> [-h] [-s] [-f] [-e] [-hp]
```

### Manage /etc/hosts

```bash
lib/manage-etc-hosts add <hostname> [<ip>]
lib/manage-etc-hosts remove <hostname> [<ip>]
```

### Manage git

```bash
lib/manage-git clone <repository> <folder> [<branch>]
lib/manage-git submodule <arguments>
```
