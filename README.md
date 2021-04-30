## <p align='center'>vim tricks ✨</p>

<p align='center'>
  Notes on various vim tricks encountered over time. Mostly as a way to remember cool stuff.
</p>

## Sorting

- `:sort` to sort lines
- `:sort!` to sort lines in reverse order
- `:sort n` to sort lines numerically
- `:%!sort -u` to sort lines alphabetically, removing duplicate lines

### Example

[![asciicast](https://asciinema.org/a/kZrHhTCOgNHBgGs5IQ9HEJmp5.svg)](https://asciinema.org/a/kZrHhTCOgNHBgGs5IQ9HEJmp5)

## Digraphs

Digraphs are `special` characters such as the copyright symbol or accent grave.

- `ctrl-K + <two letter combo>` to output a digraph (in insert mode)
- A list of defined digraphs can be found by issuing the `:digraphs` command

### Example

[![asciicast](https://asciinema.org/a/Ei8v9b4WWBF7vVyboZBoNUsHV.svg)](https://asciinema.org/a/Ei8v9b4WWBF7vVyboZBoNUsHV)

## Batch inserting

- `ctrl-v` to enter V-BLOCK mode
- `I` to edit
- `Esc` to persist changes

### Example

[![asciicast](https://asciinema.org/a/eKOAyrdaKtxd0sZqcLchLNsBp.svg)](https://asciinema.org/a/eKOAyrdaKtxd0sZqcLchLNsBp)

## Moving fast on lines

- `^` to move to the beginning of the line
- `$` to move to the end of the line
- `w` to move to the beginning of the next word
- `e` to move the the end of the next word
- `b` to move to the beginning of the previous word
- `gE` to move to the end of the previous word

### Example

[![asciicast](https://asciinema.org/a/khI5inqQovOn1b2tyujFYwX9U.svg)](https://asciinema.org/a/khI5inqQovOn1b2tyujFYwX9U)

## Aligning text

There are a few commands for aligning text horizontally in vim

- `:center` centers text
- `:left` aligns text to the left
- `:right` aligns text to the right

### Example

[![asciicast](https://asciinema.org/a/0xIOVtCTxidyWEUp73UY3lbF1.svg)](https://asciinema.org/a/0xIOVtCTxidyWEUp73UY3lbF1)
