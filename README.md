# ezplatform-rector

Configuration for [Rector](https://github.com/rectorphp/rector) to automatic upgrade eZ Platform projects

## Installation

Open a command console, enter your project directory and execute:

```console
$ composer require adamwojs/ezplatform-rector
```

## Migration

### Show suggested changes


```console 
$ vendor/bin/rector process src -c vendor/adamwojs/ezplatform-rector/config/ezplatform-2.5.7-3.0.0.yaml --dry-run 
```

### Apply suggested changes

```console 
$ vendor/bin/rector process src -c vendor/adamwojs/ezplatform-rector/config/ezplatform-2.5.7-3.0.0.yaml  
```
