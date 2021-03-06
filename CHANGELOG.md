# Changelog

## 0.1.3 (2020-01-27)

* Use `unimplemented!` macro instead of `todo!` to support Rust 1.38.0. ([#5])

[#5]: https://github.com/azriel91/tynm/pulls/5

## 0.1.2 (2020-01-10)

* `TypeName::new::<T>()` returns a `TypeName` instance for `T` without constructing the String. ([#3])
* `TypeName::as_display()` and `TypeName::as_display_mn()` both return a `TypeNameDisplay`, allowing one to pass around a `Display` object. ([#3])

[#3]: https://github.com/azriel91/tynm/pulls/3

## 0.1.1 (2020-01-02)

* Support named primitive types (`usize`, `u*`, ..). ([#1])
* Support arrays, slices, and tuples. ([#1])

[#1]: https://github.com/azriel91/tynm/issues/1

## 0.1.0 (2019-12-30)

* `tynm::type_name` returns the simple type name.
* `tynm::type_namem` returns the type name with a chosen number of most significant module segments.
* `tynm::type_namen` returns the type name with a chosen number of least significant module segments.
* `tynm::type_namemn` returns the type name with a chosen number of most and least significant module segments.
