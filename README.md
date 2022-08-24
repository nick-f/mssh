# mssh

Easily connect to multiple SSH hosts and synchronise commands

## Installation

Installation using homebrew is recommended.

```
brew install nick-f/labs/mssh
```

### Manual installation

- Ensure that `tmux` is installed
- Clone the repository
- Symlink `mssh` to a directory included in `$PATH`

## Usage

```
mssh
```

You will be prompted for the hosts to connect to.

Piping a space separated list of hosts is supported. This is handy if you are retrieving the list of hosts from another process.

```
echo "host1 host2" | mssh
```

Providing the hosts as parameters is also supported.

```
mssh host1 host2
```
