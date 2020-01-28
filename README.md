# Introduction

Small benchmark to tell which url parsing library is better.
* Node URL default class
* FastUrlParser (https://www.npmjs.com/package/fast-url-parser) 444,852 weekly dls
* parseurl (https://www.npmjs.com/package/parseurl) 11,124,454 weekly dls
* url-parse (https://www.npmjs.com/package/url-parse) 6,518,724 weekly dls

These are the results:

```
urlparse x 56,192 ops/sec ±0.54% (92 runs sampled)
Node#URL x 73,660 ops/sec ±1.13% (92 runs sampled)
parseurl x 126,538 ops/sec ±0.29% (87 runs sampled)
FastUrlParser x 374,365 ops/sec ±0.51% (91 runs sampled)
```
**Fastest is FastUrlParser**

The PC was:
Windows 10 Pro 64 bit
Intel Core i5-4590 3.3Ghz
8gb RAM
NodeJs v10.16.3
Test ran on 2020-01-28 with latest versions of all packages
