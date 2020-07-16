# Compilation docker action

This action prints "Compile main.c" or "Compile" + the name of a file to be compiled to the log.

## Inputs

### `what-to-compile`

**Required** The name of the file to be compiled. Default `"main.c"`.

## Outputs

### `time`

The completion time of compilation.

## Example usage

uses: actions/compile-docker-action@v1
with:
  what-to-compile: 'Source Code'
