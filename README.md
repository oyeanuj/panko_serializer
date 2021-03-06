# Panko

[![Build Status](https://api.travis-ci.com/yosiat/panko_serializer.svg?branch=master)](https://travis-ci.com/yosiat/panko_serializer)

Panko is library which is inspired by ActiveModelSerializers 0.9 for serializing ActiveRecord/Ruby objects to JSON strings, fast.

To achieve it's [performance](https://panko.dev/docs/performance.html):

* Oj - Panko relies Oj since it's fast and allow to to serialize incrementally using `Oj::StringWriter`
* Serialization Descriptor - Panko computes most of the metadata ahead of time, to save time later in serialization.
* Type casting — Panko does type casting by it's self, instead of relying ActiveRecord.

To dig deeper about the performance choices, read [Design Choices](https://panko.dev/docs/design-choices.html).


Support
-------

- [Documentation](https://panko.dev/docs)
- [Getting Started](https://panko.dev/docs/getting-started.html)
- Join our [slack community](https://pankoserializer.herokuapp.com/)

License
-------

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

