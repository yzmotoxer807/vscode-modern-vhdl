# VSCode Modern VHDL Support

[![Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/rjyoung.vscode-modern-vhdl-support.svg)](https://marketplace.visualstudio.com/items?itemName=rjyoung.vscode-modern-vhdl-support)
[![Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/rjyoung.vscode-modern-vhdl-support.svg)](https://marketplace.visualstudio.com/items?itemName=rjyoung.vscode-modern-vhdl-support)
[![Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/rjyoung.vscode-modern-vhdl-support.svg)](https://marketplace.visualstudio.com/items?itemName=rjyoung.vscode-modern-vhdl-support)
[![Build Status](https://travis-ci.com/richjyoung/vscode-modern-vhdl.svg?branch=master)](https://travis-ci.com/richjyoung/vscode-modern-vhdl)
[![License](https://img.shields.io/github/license/richjyoung/vscode-modern-vhdl.svg)](https://github.com/richjyoung/vscode-modern-vhdl)

This extension add language support for VHDL, based on the 2008 standard. Also includes syntax highlighting of constants, types and functions for the following standard packages:

* STD
  * standard
  * env
  * textio
* IEEE
  * std_logic_1164
  * numeric_std
  * math_real
  * math_complex
  * float_pkg
  * fixed_pkg

The core grammar definition has been written in [YAML](https://yaml.org/), to allow easier maintenance and contributions. It has been designed to be as permissive as possible, whilst enforcing syntactically correct design units and control statements.

## Features

* Syntax highlighting of VHDL files up to the 2008 standard.
* Snippets:
    * Primary & Secondary Units.
    * `if`/`case`/`for`/`generate`.
    * Range types: `std_logic_vector`/`signed`/`unsigned`.
* Completions:
    * Standard libraries & packages (STD, IEEE).

## Coming Soon

* Control Statement Snippets
* Completions
* Symbol Extraction

## Release Notes

This is extension is under active development, and changes in each release are documented in the [CHANGELOG](./CHANGELOG.md)

---
_Copyright (c) 2019 Rich J. Young_