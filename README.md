# iwd
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

**Initial Working Directory** is used for accessing project root in node require and import calls via `~/~`

### Installation
- Install `iwd` package as global module
```
npm i -g iwd
// or
yarn global add iwd
```
- Installing `~` package via `iwd`
```
iwd install
```
> Installation can use either yarn or npm
> Checkout various option below before proceding further
### Usage
It is very simple to access root directory via using `~/~`  Example :

```
const something = require('~/~/package.json')
// or
import something from "~/~/app.js"
```
With `~/~/` you get access to your project's root directory and then you can simply access your files/folders via that.

### Options

| Option | Description |
|--|--|
| i, install | install the `~` package. `iwd i` |
| r, remove | remove the `~` package. `iwd r` |
| -h, help, options | used to display all available options. `iwd -h` |
| -v, version | version of `iwd` package. `iwd -v` |
| -y, yarn | used in conjunction with `i` command to use yarn while installing `~` package. `iwd i -y`|
| -d, dev | use to install the `~` package as a dev dependency. `iwd i -d` or `iwd i -y -d`|

### Contact  
  
+ Twitter - [@dawnimpulse](https://twitter.com/dawnimpulse)  
+ Email - [dawnimpulse@gmail.com](mailto:dawnimpulse@gmail.com)
  
    
  
### License (ISC)  
~~~~
ISC License  
  
Copyright 2020, Saksham (DawnImpulse)  
  
Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted,  
provided that the above copyright notice and this permission notice appear in all copies.  
  
THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL  
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,  
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS,  
WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE  
OR PERFORMANCE OF THIS SOFTWARE.
~~~~

> Written with [StackEdit](https://stackedit.io/).