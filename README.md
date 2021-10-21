# Espanso Config

Personal config file for [espanso](https://espanso.org), incredible power of a full-blown text expander for multiplatform.

## 1) Installing espanso

```bash
$ brew tap federico-terzi/espanso
$ brew install espanso
$ espanso register
```

Or download it from [espanso download page](https://espanso.org/install/).

## 2) Download this repo on your home directory

```bash
$ cd ~
$ git clone git@github.com:nalmeida/espanso-config.git
```

## 3) Linking espanso config to this repo

### For mac (11.5.2)

```
$ ln -s "$HOME/espanso-config" "$HOME/Library/Preferences/espanso"
$ espanso start
```

### Other options

Original espanso config location: `~/Library/Preferences/espanso/default.yml`

You need to create a symbolic link from the espanso to this repo. [All options / OS instructions available here](https://espanso.org/docs/sync/).
