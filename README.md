# Spacing-responsive

The `spacing-responsive` module provides breakpoint-based classes for
nudging margins and paddings around responsively, e.g. `.lap-mb0`, `.desk-mb++`.

## Dependencies

The `spacing-responsive` module depends on four other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tree-responsive-settings](https://github.com/treeframework/settings.responsive)
* [tree-responsive-tools](https://github.com/treeframework/tools.responsive)
* [tree-spacing](https://github.com/treeframework/trump.spacing)

If you install the `spacing-responsive` module using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and `@import` these dependencies in the relevant way.

## Installation

You can install `spacing-responsive` module via Bower, npm, Git Submodule, or copy and
paste.

### Install using Bower:

```sh
$ bower install tree-spacing-responsive --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-spacing-responsive/trump.spacing-responsive";
```

### Install using npm:

```sh
$ npm install tree-spacing-responsive --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/trump.spacing-responsive.git
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "trump.spacing-responsive/trump.spacing-responsive";
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.spacing-responsive.scss` into your project and `@import` it into your
project in its Trump layer.

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
