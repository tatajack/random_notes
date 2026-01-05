# random_notes

## ssh jumping

### socks proxy

```
$ ssh -ND 8888 user@server
```

## random sleep

### gnu bash

```
$ sleep $(echo "${RANDOM}" | cut -b 1)s
```

```
brew install coreutils
alias date=gdate
alias cut=gcut
```

```
read -t 10 -p "ENTER to continue" || echo ""
```

## time strings

### bash
``` bash
date "+%Y%m%d_%H%M%S"
```

### python 
``` python
time.strftime("%Y%m%d_%H%M%S") -> '20201116_113252'
```
