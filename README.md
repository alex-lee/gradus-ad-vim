# gradus ad vim

> Note: this is very much a work in progress

For one who is new to [vim]/[neovim], it is hard to know where to start, and there are many
resources out there.

This is meant as a very quick roadmap of the most useful commands. I've tried to only include
commands that one will use on a daily basis, and the ordering is intended to get you moving as
quickly as possible. What is presented here is not comprehensive, but it should provide a pretty
good foundation.

To use these lists, just go in order. Practice each set of commands, trying to incorporate them as
much as possible in your daily editing. When you feel comfortable with them, move on to the next
set and repeat the process.

The explanations are short. To really understand what the commands do, try using them and see what
happens. For more details, refer to the vim/neovim documentation (linked below).

[vim]: https://www.vim.org/
[neovim]: https://neovim.io/

The repository name is a play on [Gradus ad
Parnassum](https://en.wikipedia.org/wiki/Gradus_ad_Parnassum).

## vim or neovim?

For basic use, both vim and neovim are very similar. It is worth mastering the functionality common
to both. For more advanced usage, these days I prefer neovim.

In this repository, I use "vim" to refer to either editor.

## Modes

When using vim, the editor can be in several modes. Various commands or keys can change the mode.

To start, these are the most important modes:

- `[N]` Normal: You type in commands.
- `[I]` Insert: You type text that goes into the buffer.
- `[C]` Command-line: You enter other commands, at the bottom of the screen.
- `[V]` Visual: You select text in the buffer.

See also `usr_02.txt` in the User Manual.

## Notation

Each entry follows this basic format:

```
COMMAND(S)

  [MODE] DESCRIPTION

  EXAMPLES
```

- The commands are the keystrokes that you enter.
- The mode is the mode where you can use the command. If the command changes the mode, this is
  indicated with an arrow, e.g. `[N→I]`.

## Resources

Here are links to the documentation for each editor. The user manual is worth reading through at
some point.

- neovim
  - [Neovim User Manual]
  - [Neovim Documentation]

- vim
  - [Vim User Manual]
  - [Vim Documentation]

[Neovim Documentation]: https://neovim.io/doc/user/
[Neovim User Manual]: https://neovim.io/doc/user/usr_toc.html#user-manual
[Vim Documentation]: https://vimdoc.sourceforge.net/htmldoc/help.html
[Vim User Manual]: https://vimdoc.sourceforge.net/htmldoc/usr_toc.html
