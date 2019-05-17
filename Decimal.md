# ECMAScript proposal: Decimal numbers
- [Motivation](#motivation)
- [High-level API](#high-level-api)
- [FAQ](#faq)

## Motivation

Fixed precision and scale numbers like ISO decimal numbers: dec and dec(p, s)
Where p (precision) - maximum total number of decimal digits,
s (scale) - number of decimal digits that are placed to the right of the decimal point
This will help solve the problem of performing financial calculations 
and realize integer arithmetic (with s = 0)

## High-level API

```js

var number = new Decimal(18, 4)


```
