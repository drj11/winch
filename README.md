## Winch

`winch` reports the X and Y size of the current tty, and
continue to report it when the WINdow CHanges size:

```
$ winch
Change window size; press ^C to exit.
80 24^C
```

It is of course named after the `SIGWINCH` Unix signal.

Install with

```
npm install winch
```

If you have `npm`.
