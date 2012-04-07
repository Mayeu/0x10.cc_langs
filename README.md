# 0x10.cc langs

This repository contains the translation for 0x10.cc website

## data

Data contains yaml file representing the Q&A database.

### Questions representation

A question have the following field :

   - question: My awesome question
     answer: The awesome answer from Notch
     title_id: X
     links:
     - url: first url
       link_name: name of the first url
     - url: second url
       link_name: name of the second url

You can have as many url and link name you want.
The title id should be one of the following number:

   1: The game
   2: The graphics
   3: The computer
   4: Capability of the computer
   5: Space, hardness, and physics related
   6: Technically advanced part

### Ordering

Currently the database do not have any timestamp on item. Last are recent, and the
order in the file is the order on the website.

### Filename

The database file should be named like this:

   db_<lang>_question.yml
   db_<lang>_theme.yml

## locales

Contains yaml file for translating the fixed content of the website.

### Filename

The locales file should be named like this:

   <lang>.yml
