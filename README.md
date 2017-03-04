# Sass Flexbox Mixins
A set of Sass mixins for Flexbox.

### About
This is not a full fledged grid system, and does not try to be.

It is a set of functions and mixins to quickly and deliberately layout a page, component, etc. using flexbox. Flexbox is not as difficult as people believe it is, nor does it require as much markup as many will lead you to believe.

## Usage
There are only 2 parts to using these mixins: defining your flex parent, and defining its children.

### Defining flex parents
```
.parent {
  @include grid();
}
```

### Defining flex children
```
.column {
  @include column();
}
```
