# Diagon GUI plugins

## Instalation

1. Patch `kgt` for no-exit code:

```
kgt-src % patch < ../../../plugins/patch/kgt-no_exit.diff
patching file 'src/abnf/parser.c'
patching file 'src/bnf/parser.c'
patching file 'src/iso-ebnf/parser.c'
patching file 'src/parsing_error.h'
patching file 'src/rbnf/parser.c'
patching file 'src/wsn/parser.c'
```
