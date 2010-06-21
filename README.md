# TextMate macro for increasing your uber-ness

This macro automatically removes your "diff cruft" with;
  Convert Tabs To Spaces, And
  Remove Trailing Whitespace

when you use the Save Cmd (⌘S)

Original idea: Christopher R. Murphy : http://blogobaggins.com/2009/03/31/waging-war-on-whitespace.html

## Installation

    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone git://github.com/glennr/uber-glory-tmbundle.git Uber\ Glory.tmbundle
    cd Uber\ Glory.tmbundle
    git submodule update --init
    osascript -e 'tell app "TextMate" to reload bundles'

## TODO

   add "All your base are belong to us" reference somewhere.

## License

Copyright (c) 2010 Glenn Roberts, Siyelo

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:
The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
