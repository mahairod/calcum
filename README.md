# Elliptica BigNum Calcum with spreadsheets
### Big Number Calculator

This is the pre-first start version of my simple calculator which serves
the need of computing with big numbers i.e. numbers with 64-bit precision
or approximately 19-digits decimal precision.

### Features

Current version includes this functionality:

- Simple spreadsheet-like view of a single document:
  - Expandable 2-dimensional table of cells
- Each cell can contain integral number, text or formula, hexademical number format is supported
- Very big numbers are supported, with mantissa up to ~ 19 decimal digits
- Formulas support basic arithmetic operations: + - * / %. There is also support for bit shifts: << and >>
- Text concatenates with +
- Formulas can use custom fuctions which can be defined separately as a simple text
  - Predefined functions are available (mostly for string/character and list processing)
- Basic cells editing, row and columns insetion preserving correct order
- Copy/cut/paste operations of cell regions inside application
  - Data export to antoher applications through clipboard as [CSV](https://en.wikipedia.org/wiki/Comma-separated_values#Example) values
- Auto filling on region expansion
  - Convenient filling with Ctrl button pressed
  - Support for non-contigous multiple regions (with some restrictions)
- Whole table recalculation on cell value change
- Opening of file in [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) format is supported
- Saving files in [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) format

![calc-x64](https://github.com/mahairod/calc/assets/7587521/a7fc8519-5ca2-4bbd-81db-f1e3b3911c88)

