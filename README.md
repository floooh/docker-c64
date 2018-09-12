# docker-c64
A C64 emulator in Docker. This is a real C64 emulator "underneath", but with a
stripped down display output (just the character buffer converted to ASCII),
and no sound output.

## Howto

Run from Docker Hub:

```
> docker --rm -it flohofwoe/c64
```

To build just the emulator:

```
> cc c64.c -o c64 -O3 -lcurses
```
