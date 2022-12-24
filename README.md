# bubbles

A wayland compositor made with zig-wlroots.


## Building

First make sure the submodules are initialized and updated with

```
git submodule update --init --recursive
```

Then simply run `zig build` to build bubbles.zig.

### dependency requirement

you may need the following dependencies to build bubbles: (currently I only test for arch linux)
- zig, (`pacman -S zig `)
- wlroots, (`pacman -S wlroots`)


## License

bubbles is released under the BSD 3 Clause license.
This license applies to all files in the repository excluding dependencies.