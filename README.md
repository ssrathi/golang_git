# golang_git
Implementation of git internal commands in Go language.

[![Go Report Card](https://goreportcard.com/badge/github.com/ssrathi/golang_git)](https://goreportcard.com/report/github.com/ssrathi/golang_git)

## Supported commands
* `gogit init <path>`
* `gogit hash-object <file_name>`
* `gogit cat-file -t|-s|-p <object_hash>`
* `gogit ls-tree <tree_hash>`
* `gogit mktree`
* `gogit checkout [-path <path>] <tree_hash>`
