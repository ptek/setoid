# Setoid

A Haskell implementation of
[setoid](https://en.wikipedia.org/wiki/Setoid) - a set equipped with
an equivalence relation. Setoid is a useful data structure when
equivalence is chosen not to be equality. This allows to influence the
membership of the elements in a setoid. When equality is all one needs
- using sets is a better option.

Here we have chosen to use a specific variant of equivalence of
transforming the elements to comparable intermediaries. Although it
does not make every equivalence relation possible, it is a practial
choice for a lot of computations.

## Usage

Please have a look at the documentation of Data.Setoid on hackage to see use cases and more in-depth explanations.


## Authors:
*  [Pavlo Kerestey](https://github.com/ptek)
*  [Irek Jozwiak](https://github.com/irekjozwiak)
*  [Simon Zelazny](https://github.com/pzel)

### Copyright: [Global Access Internet Services GmbH](http://www.global.de)

## License

```text
Copyright (c) 2017, Global Access Internet Services GmbH

All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.

    * Redistributions in binary form must reproduce the above
      copyright notice, this list of conditions and the following
      disclaimer in the documentation and/or other materials provided
      with the distribution.

    * Neither the name of Pavlo Kerestey nor the names of other
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
