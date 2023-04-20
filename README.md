![bash_unit CI](https://github.com/pforret/static/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/static/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/static)
![GH stars](https://img.shields.io/github/stars/pforret/static)
![GH tag](https://img.shields.io/github/v/tag/pforret/static)
![GH License](https://img.shields.io/github/license/pforret/static)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# static

quick install/preview/deploy for static site generators (Jekyll, Mkdocs)

## 🔥 Usage

```
Program : static  by peter@forret.com
Version : v0.0.1 (2023-04-20 13:10)
Purpose : quick install/preview/deploy for static site generators (Jekyll, Mkdocs)
Usage   : static [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /home/pforret/log/static]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/static]
    <action>         : [choice] action to perform  [options: action1,action2,check,env,update]
```

## ⚡️ Examples

```bash
# initialize a project (e.g. after a fresh git clone)
static init

# preview a SSG project (start serve & open browser)
static serve

# build a SSG projet (build site)
static build

# deploy a SSG project (build/git commit/git push)
static deploy
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/static

or with `git`

	$ git clone https://github.com/pforret/static.git
	$ cd static

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2023 Peter Forret
