# Atto

Atto is a text editor developed by Dieter Schoppitsch in the
early 2000s. Even for a line editor, it is unusually beasty.
Clearly, don't expect emacs, but don't even expect ed or
edlin.

The following is copied from the editor's homepage at
<http://web.uta4you.at/shop/atto/> which sadly is only available
at its archive entry <https://web.archive.org/web/20040618102909/http://web.uta4you.at/shop/atto/>:

> Atto is a simple, fast (doesn't need ncurses) and small
> (\<16k) line editor. <br> Nevertheless it provides features
> like a buffer, search&replace, an ascii table and a simple
> hex dumper.

> Two things are tricky:

> -   It's not possible to edit a line directly. Instead the
>     line is printed and an "edit string" will be read below.
>     -   Everything after an `'i'` in this string will be
>         inserted in the line.
>     -   Everything after an `'d'` in this string will be
>         deleted in the line.
>     -   Everything after an `'c'` in this string will be
>         changed in the line.
>     -   A `'s'` in this string splits the line.
> -   Inserting new line(s) after the actual line (command `'i'`)
>     could be ended with a `'.'` in a line itself.

> Get some further help by pressing `'h'` after starting the
> program.

> Compile with: `gcc -Wall -s -O3 a.c`

> I wrote atto as reminiscence to my first programming lesson
> 1981 on a honeywell bull host.

> Feel free to improve this program under the conditions of the
> general GNU-license-agreement.
