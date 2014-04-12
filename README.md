angular-tree-selection-directive
================================

[Demo](http://baldurh.github.io/tree-selection-directive/)

```
tree = [
  {
    text: 'Number 1',
    open: true, /* optional */
    subLevel: [
      { 
        text: 'Number 1.1',
        subLevel: [
          {
            text: 'Number 1.1.1'
          },
          {
            text: 'Number 1.1.2',
            subLevel: [
              {
                text: 'Number 1.1.2.1'
              },
              {
                text: 'Number 1.1.2.2'
              }
            ]
          },
          {
            text: 'Number 1.1.3'
          }
        ]
      }
    ]
  },
  {
    text: 'Number 2',
    subLevel: [
      { 
        text: 'Number 2.1',
        subLevel: [
          {
            text: 'Number 2.1.1'
          },
          {
            text: 'Number 2.1.2',
          }
        ]
      }
    ]
  }
];
```

Licence
-------

This code is released under the [MIT Licence](http://opensource.org/licenses/MIT)

Copyright (c) 2014 Baldur Helgason

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
