# etak-words submodule

This directory is a git submodule pointing to:
  https://github.com/charlesrobsampson/etak-words

After cloning, run:
  task setup
or:
  git submodule update --init --recursive

The submodule contains a single file: words.txt
  - One word per line
  - 3000 words total
  - Order is fixed and matches words.go exactly
  - Do not reorder — position = encoding index

To regenerate all derived files after updating the word list:
  task generate
