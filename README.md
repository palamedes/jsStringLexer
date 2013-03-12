# jsStringLexer

---

The following javascript library is meant to be a string lexing tool set.

All methods in this library are published within the namespace ```jsStringLexer```.

Currently the following methods are available;

**Method** ```Array jsStringLexer.csv2array(String csv)```

Takes a CSV string and parses it into an array of arrays.  Each line is it's own array.

There are a number of different csv to array javascript functions out there but none of them correctly parsed out the data that my client was sending which was slightly off from the known spec.

Example:

-    jsStringLexer.csv2array('"foo","a\\"b\\"c,bar","baz");


## Contributing

You can fork/fix/add/pull request this repo, and I'll gladly add your code ;)

## Contributors

If you issue a pull request, add your name here!

## License

MIT License - http://opensource.org/licenses/MIT

Copyright (c) 2013 Jason Ellis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.