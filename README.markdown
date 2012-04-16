## normalize.scss

This is a Sass version of [normalize.css](http://necolas.github.com/normalize.css/)
by Nicolas Gallagher and John Neal.

It is created in such a way, that individual parts of normalize.css can be
included on their own.

### Usage:

    @import "normalize";
    @include normalize;

The mix-in "normalize" is basically a placeholder for all the submodules. You
can use them directly, if you like:

    @include normalize-display;
    @include normalize-base;
    @include normalize-links;
    @include normalize-typography;
    @include normalize-lists;
    @include normalize-embedded;
    @include normalize-figures;
    @include normalize-forms;
    @include normalize-tables;

### License

Public domain. The first line of normalize.scss includes an CSS comment
attributing the original nromalize.css authors. I suggest to keep that in your
project.
