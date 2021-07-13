Notes on a-n-t-h-o-n-y/Escape
=============================

## Overview 

Notes on [escape](https://github.com/a-n-t-h-o-n-y/Escape).

## Notes

Did not know about `std::c32rtomb` -- converts a c32 representation
to its multibyte representation

`std::visit` and `std::variant` seem to allow some sort of pattern
matching in a way...yep that is what seems to work. Generic lambdas

Cmake has a `check_ipo_supported` if one includes `CheckIPOSupported`.
Can be used to see if `lto` is possible.

`[[nodiscard]]`` is great -- allows you to specify compiler warnings
if a return is ignored!
