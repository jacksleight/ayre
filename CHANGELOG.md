# Changelog

### 0.1.0

* Initial release

### 0.2.0

* Simpler and more logical defaults
* Ability to omit auto argument from mixins and funcs
* More efficient breakpoint width generation
* Simpler and cleaner media query output
* More predictable behaviour when overriding auto spans

### 0.2.1

* Option to set default item font size
* Rename basis variable
* Refactor span length functions to be more intuitive

### 0.2.2

* Flip span length function arguments

### 0.2.3

* Allow string length values, eg. 'auto'

### 0.2.4

* I messed up the version numbering

### 0.2.5

* Fix length calculations when using scaled values below the max limit

### 0.3.0

* (BREAKING) Whitespace is now removed using a no whitespace font-face rather than setting the font-size to 0, $ayre-font-size has been removed and replaced with $ayre-font-family
* (BREAKING) Gutters are no longer taken into account when calculating breakpoint sizes

### 0.3.1

* Add abiltiy to use mixin for font-family reset

### 1.0.0

* Add $ayre-pixel variable to set 1 pixel size when using other units

### 1.0.1

* Add font-display to no-whitespace font

### 1.0.2

* Fix overriding gutters to 0

### 1.0.3

* Support specifying extra as a percentage or vw uint
