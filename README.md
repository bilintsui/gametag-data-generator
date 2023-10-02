# GameTag module Data Generator
Generate a qualified Lua table for Chinese Minecraft Wiki Module "GameTag"

## Prerequisites
* Linux
* findutils (Debian / Fedora / Arch: `findutils`)
* Perl (Debian: `perl-base`; Fedora: `perl-core`; Arch: `perl`)
* JSON module for Perl (Debian: `libjson-perl`; Fedora: `perl-JSON`; Arch: `perl-json`)

## Files
* `generator`: Data Generator, but not include experimental datapacks.
* `generator_full`: Data Generator, with all experimental datapacks.

## Usage
You need to change your working directory to `data/minecraft` in the game jarfile before the execution.

Then type `./generator` or `./generator_full` in the working directory. Once it finished, the generated table will output on the screen.
