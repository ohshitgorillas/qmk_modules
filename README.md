# ohshitgorillas' QMK Community Modules

In this repository are the QMK community modules that I've written. Each is discussed below.

To add these modules to your QMK, execute the following commands:
```bash
cd /path/to/your/external/userspace
git submodule add https://github.com/ohshitgorillas/qmk_modules.git modules/ohshitgorillas
git submodule update --init --recursive
```

## xcase
xcase is a module which allows for replacing spaces with arbitrary delimiters. This makes it very easy to:
- enter_long_variable_names_in_snake_case
- orEvenCamelCase 
- and-kebab-case-too
- or/even/use/arbitrary/delimiters/like/slashes/for/long/file/path/names

More information is in the [xcase repository](https://github.com/ohshitgorillas/qmk-xcase).

## spOngEmoCk
SpongeMock is a module which randomly capitalizes letters as you type lIkE iN thE spONgeBob mOckiNG mEmE.

More information is in the [SpongeMock repository](https://github.com/ohshitgorillas/spongemock).

## BadKeys
BadKeys is a module which allows you to train yourself against using certain keys or functions by having your keyboard emit a sound whenever the specified keycode or keypress is registered.

More information is in the [BadKeys README](badkeys/README.md).
