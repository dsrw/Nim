# v1.8.x - yyyy-mm-dd


## Changes affecting backward compatibility



## Standard library additions and changes

## Standard library additions and changes

- `macros.parseExpr` and `macros.parseStmt` now accept an optional
  filename argument for more informative errors.
- Module `colors` expanded with missing colors from the CSS color standard.
- Fixed `lists.SinglyLinkedList` being broken after removing the last node ([#19353](https://github.com/nim-lang/Nim/pull/19353)).
- `macros.parseExpr` and `macros.parseStmt` now accept an optional
  filename argument for more informative errors.

## `std/smtp`


## Language changes



## Compiler changes

- `nim` can now compile version 1.4.0 as follows: `nim c --lib:lib --stylecheck:off compiler/nim`,
  without requiring `-d:nimVersion140` which is now a noop.


## Tool changes



