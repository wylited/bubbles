# bubbles

A wayland compositor made with zig-wlroots.


## Building

First make sure the submodules are initialized and updated with

```
git submodule update --init --recursive
```

Then simply run `zig build` to build bubbles.zig.

### dependency requirement

you will need the following dependencies (and possibly others) to build bubbles:
- zig, (`pacman -S zig `)
- wlroots, (`pacman -S wlroots`)


## Goals

What makes bubbles different from literally every other wayland compositor?

Here are some features I aim to implement:
- [ ] Leader based mneumonic key bindings (similar to doom emacs evil bindings)
- [ ] Highly configurable and intuitive window tiling
- [ ] Easily customizable window decorations
- [ ] Low power draw on idle 
- [ ] Scratchpads or scratch workspaces
- [ ] Support freeBSD
- [ ] Inbuilt redshift
- [ ] Easy remote desktoping?

## License

bubbles is released under the BSD 3 Clause license.
This license applies to all files in the repository excluding dependencies.
