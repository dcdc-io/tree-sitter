cpp build

`clang -g -O0 -I ../lib/include test-mustard-parser.c ./tree-sitter-mustard/src/parser.c ./tree-sitter-mustard/src/scanner.c ../libtree-sitter.a -o test-mustard-parser`