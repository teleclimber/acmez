Go ACME client implementation
=============================

**Work in progress. Still under heavy development -- do not use.** For now, use [lego](https://github.com/go-acme/lego).

However, most Go programs probably want [CertMagic](https://github.com/caddyserver/certmagic) instead of a low-level ACME library like this or lego.

For the time being, this project is a fork of lego, which was originally written for use in Caddy by Sebestian Erhart (xenolf).

This repository is licensed with Apache 2.0 open source license.

The upstream repo has this license, which is included here for compliance as long as we share its code base:

```plain
The MIT License (MIT)

Copyright (c) 2015-2017 Sebastian Erhart

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```