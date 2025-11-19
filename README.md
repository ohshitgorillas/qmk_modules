# ohshitgorillas' QMK Community Modules

Welcome to my collection of custom QMK modules!

## Installation

These modules are designed to be easily added to any QMK userspace as a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

From the root of your QMK userspace repository, run the following commands:
```bash
git submodule add https://github.com/ohshitgorillas/qmk_modules.git modules/ohshitgorillas
git submodule update --init --recursive
```

This will add the modules to the `modules/ohshitgorillas` directory within your userspace. Then, you can enable individual modules in your `keymap.json`.

## Available Modules

### xcase

A module for replacing spaces with arbitrary delimiters as you type, making it incredibly easy to write in different code casing styles without interrupting your flow.

**Examples:**
- `enter_long_variable_names_in_snake_case`
- `orEvenCamelCase`
- `and-kebab-case-too`
- `or/even/use/arbitrary/delimiters/like/slashes`
- `youacanaevenareplaceaspacesawithaletters`

For more details, see the [xcase repository](https://github.com/ohshitgorillas/qmk-xcase).

### spOngEmoCk

a mODuLe wHiCh rAnDoMlY caPiTaLiZeS leTtErS aS yOu tYpE lIkE iN thE spONgeBob mOckiNG mEmE.

Perfect for when you need to make a point, sarcastically.

More information is in the [SpongeMock repository](https://github.com/ohshitgorillas/spongemock).

### BadKeys

Break bad habits and train your muscle memory. `BadKeys` helps you avoid using certain keys or key combinations by emitting an audible alert whenever you press them. It's a great tool for weaning yourself off inefficient keys (like the arrow keys) and reinforcing better habits.

More information is in the [BadKeys README](badkeys/README.md).
