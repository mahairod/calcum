---
# Calcum home page

layout: page
---

# Calcum
### Big Number Calculator

This is the site of
<span style="color:green"> *spreadsheet* </span>
calculator which serves the need of calculations with
<span style="color:green"> *big numbers* </span>
i.e. numbers with 64-bit precision
or approximately *19-digits* decimal precision.


### Features

Calcum offers simplified syntax for mathematical operations:
they look like regular operators in a typical math formula.
The app also handles raw text.

Calcum supports several predefined arithmetic and string functions.

Additional functionality can be implemented by custom functions. You can write them using
built-in operators and functions.

#### Technical details
BigNum Calcum makes computations in integer arithmetic with
numbers represented by exactly 64 bits. It is able to handle large integer numbers
with more than 15 digits in a decimal value representation.
So additionally it can process numbers with 16 to 19 decimal digits.
There is no limitation of standard Excel-style (or LibreOffice Calc-style) computations in double-precision floating-point format
which gives you at most 14 or 15 digits precision and rounding errors for values exceeding this limit.

### Releases

I'm glad to announce that first version of Big Number Calculator (Calcum) is
available for public

Here you can find an installer for windows: [link](https://github.com/mahairod/calcum/releases/tag/v0.6.4-alfa)

Hope this app would be usefull for you.

#### Here's the full list of releases:
{% for release in site.releases %}
  - [{{ release.title }}]({{ release.url }})
{% endfor %}
