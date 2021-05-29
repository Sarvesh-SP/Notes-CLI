# cNote

- Simple cli for making notes.
  <br>

<div align="center">

  <br>
  
  <br>

[![Badge](https://img.shields.io/badge/Uses-Node.js-green.svg?style=flat-square)](Node.js)
[![Badge](https://img.shields.io/badge/Open-Source-important.svg?style=flat-square)](OpenSource)
[![Badge](https://img.shields.io/badge/Made_with-Love-ff69b4.svg?style=flat-square)](MadeWithLove)

  <br>

</div>

## Installation:

- Install [Node.js](https://nodejs.org/en/),
- Clone this repo: `git clone https://github.com/Ythosa/whynote`,
- Install dependences by writing in console: `npm install`,
- Setup module by writing in console: `npm link --force`,
- Done, you can use it from your `cmd`.

<br>

## Description:

- Command line notebook;
- `cNote` is easy way to note tasks, which need to be completed;
- It is easy to install and easy to use;
- It has great functionality.

<br>

<h2 align="center"> :.Documentation.: </h2>

### cNote's Commands:

- #### Get cNote help:
  - `note --help|-h [command]`.
  - commands are:
  - `add`
  - `list`
  - `remove`
  - `modify`
- #### Get cNote version:
  - `note --version|-V`.
- #### Get list of notes:
  - `note list|l [options] `,
  - Options could be:
  - `--help|h` - get info about this function.
- #### Adding notes:
  - `note add [options]`,
  - You will need to enter | options:
    - `--t=`"Notes's title",
    - `--b=`Content/Body of the notes`;
  - `--help|h` flag exists to get info about this function.
- #### Removing notes:
  - `note remove|rv <id>`,
  - Removing notes from note list with id,
  - Id can be:
    - `id`, note number in note list,
    - `all`, by this way you can remove all notes from note list,
    - `--t=`, by the title;
  - `--help|h` - get info about this method.
- #### Modification task:

  - `note modify [options]`,=
  - Options could be:
  - `id`, based on the id,
  - `--t`, based on the title, 
  - Yet to be added(Above features Not available)
  - `--help|h`.

<br>

<div align="center">
  Copyright 2021 sarveshSP
</div>
