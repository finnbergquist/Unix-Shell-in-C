# Shell

This shell supports unix-style job control. It repeatedly prints a prompt, waits for a program name and command-line arguments on stdin (i.e., the terminal window), then carries out some action as directed by the input. Some things that this shell can do include parsing command line input, running forgrounded and background processes, forking child processes, and processing signal handlers.

## Project Structure

- `bsh`: The main shell program
- Additional utility programs:
  - `myspin`
  - `mysplit`
  - `mystop`
  - `myint`

## Compilation

To compile all necessary files, run:

```
make all
```

## Running Tests

### Shell Tests

To run tests using the shell implementation:

```
make test01
make test02
...
make test16
```

### Reference Shell Tests

To run tests using the reference shell implementation:

```
make rtest01
make rtest02
...
make rtest16
```

## Cleaning Up

To remove compiled files and clean the directory:

```
make clean
```

## Requirements

- gcc compiler
- Perl (for running the driver script)
