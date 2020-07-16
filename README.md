# README

**rm-trash** is a utility for safely remove (`rm`) files in Terminal.app of macOS.

![rm-trash](https://gw.alipayobjects.com/mdn/wealth_prod/afts/img/A*qYewRpNt2M8AAAAAAAAAAABjARQnAQ)

## INSTALL

```bash
$ npm i rm-trash -g
```

## USAGE

```bash
$ rm-trash file
$ rm-trash dir
$ rm-trash link
```

Optional: set an alias to `rm-trash` for easier to use the commend.

.zshrc or .bash_profile

```sh
$ alias rm="rm-trash"
```

p.s. The origin `rm` commend is `/bin/rm`.

## Configuration

add `~/.rm-trash-ignore` to direct remove files.

Example:

```txt
/node_modules
```
