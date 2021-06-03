# Go: The Complete Developer's Guide

[![udemy](https://img.shields.io/badge/Udemy-Go--The--Complete--Developers--Guide-EC5252?logo=udemy&style=flat-square)](https://www.udemy.com/course/go-the-complete-developers-guide/)


## Installation

### Golang

To be able to manage multiple Golang versions besides each other install `goenv`. The brew package was not updated for
quite some time so use the following command to get the latest version directly from the repository.

`brew install --HEAD goenv`

Add the following lines to your shell config (e.g. `.zshrc`) so that the installed Golang version will be picked up
correctly in your shell.

```
eval "$(goenv init -)"
export GOPATH="$HOME/go"
export PATH="$PATH:$GOPATH/bin"
```


### VSCode

Install VSCode togehter with the Go language support extension. The IDE will ask you to install some support tools via
Golang to perform linting etc. once you opened the first Golang file.