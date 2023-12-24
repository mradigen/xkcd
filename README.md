# xkcd

Minimal script to read xkcd comics (https://xkcd.com/).

## Dependencies:

-   `curl`
-   `feh`

## Usage:

```sh
xkcd                             # Get the latest xkcd comic from https://xkcd.com/
xkcd {n}                         # Get a specific xkcd comic from https://xkcd.com/
xkcd [OPTIONS] {n}

Options:
	-r, --random                 # Get {n} number of random xkcd comic(s)
	-c, --check                  # Check whether a new comic was released
	-h, --help                   # Output this help
```
