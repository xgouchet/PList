PLIST
====

PList is a library designed to parse binary PList files. This library was first designed to be used inside the Axel app, available on [Google Play](https://play.google.com/store/apps/details?id=fr.xgouchet.xmleditor) and [GitHub](https://github.com/xgouchet/Axel). 

USAGE
=====

The parser returns a hierarchy of objects which mimic the NSArray, NSDict, and NS* objects in Java. 

The following code will parse a file and result in an object : 

```java
File file = ... 
PObject obj = 
new PlistParser().parse(new FileInputStream(file));
```


LICENCE
=======

Copyright (C) 2012 by Xavier GOUCHET (http://xgouchet.fr, android@xgouchet.fr)
MIT Licence / Expat

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
AUTHORS ( XAVIER GOUCHET ) BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.