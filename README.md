# jnh
Start a BASH shell within a Docker container:

```bash
$ jnh container_name
```

Comes with container name completion on the shell.

Name inspired by [Jonah](https://en.wikipedia.org/wiki/Jonah), famous for spending 3 days within a whale.

## Setup

Just make sure that the `jnh` script is executable and on your path and that `jnh.completion` is loaded by your shell bootstrap script (e.g. `.bashrc`):

```bash
export PATH="$PATH:/path/to/repo/bin"
source /path/to/repo/jnh.completion
```
