# counsel-gtags.el

[GNU GLOBAL](https://www.gnu.org/software/global/) interface of [ivy](https://github.com/abo-abo/swiper).

This package is still developing.

## Tasks

- [X] Basic commands
- [X] find file command
- [X] Tag command
- [ ] Context command(dwim)
 - [X] Find definition and references
 - [ ] include header support
- [ ] `GTAGSLIBPATH` support
- [X] Basic History command
- [ ] History navigate command
- [ ] Tramp support
- [ ] Windows support

## Installation

counsel is not registered MELPA yet.

## Basic Usage

#### counsel-gtags-find-definition

Move to definition

Move command push current position to stack. `counsel-gtags-pop` command pops point stack and jump back to previous point.

#### counsel-gtags-find-reference

Move to references

#### counsel-gtags-find-symbol

Move to symbol references

#### counsel-gtags-find-file

Find file from tagged files

#### counsel-gtags-pop

Move to previous point on stack

#### counsel-gtags-create-tags

Create GNU GLOBAL tag

#### counsel-gtags-update-tags

Update tags.

#### counsel-gtags-dwim

Find name by context.

- Jump to tag definition if cursor is on tag reference
- Jump to tag reference if cursor is on tag definition
