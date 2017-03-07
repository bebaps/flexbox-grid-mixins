# Sass Flexbox Mixins
A set of Sass mixins for Flexbox

### About
This is not a fully fledged grid system, and does not try to be.

It is a set of Sass functions and mixins to quickly and deliberately layout a page, component, etc. using flexbox. Flexbox is not as difficult as people believe it is, nor does it require as much markup as many will lead you to believe.

## Usage
There are only 2 parts to using these mixins: defining your flex parent, and defining its children.

***NOTE: each function and mixin is documented inline, but is in the process of being outlined here for ease.***

### Defining the Flex Parent
```
.parent {
  @include grid();
}
```

### Defining Flex Children
```
.child {
  @include column();
}
```

# TODO
- Write complete documentation in the README
- A demo page, like every other grid
