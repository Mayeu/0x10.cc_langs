# 0x10.cc langs

This repository contains the translation for 0x10.cc website

## data

The data folder contains yml files representing the Q&A database.

### Questions representation

A question have the following fields:

    - question: My awesome question
      answer: The awesome answer from Notch
      title_id: X
      links:
      - url: first url
        link_name: name of the first url
      - url: second url
        link_name: name of the second url

You can have as many url and link names as you want.
The title id should be one of the following numbers:

    1: The game
    2: The graphics
    3: The computer
    4: Capability of the computer
    5: Space, hardness, and physics related
    6: Technically advanced part

### Ordering

Currently the database does not have any timestamps on the item. Last are more recent, and the
order in the file is the order on the website.

### Filename

The database files should be named like this:

    db_<lang>_question.yml
    db_<lang>_theme.yml

## locales

Contains yml files for translating the fixed content of the website.

### Filename

The locales files should be named like this:

    <lang>.yml


Thank you,

-Mayeu