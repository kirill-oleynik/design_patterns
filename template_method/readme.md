# Problem

Something right in the middle of complex code need to vary.

And in future this thing will need to do something else.

## Violation:

- mixeing up code that is changing with code that is not changing

### Example:

Coding a `Report` obect that creating same report in different formats.

First of all we need to extract parts that always stay the same from the parts
that varies.

Abstract class will contain only abstract methods without realization.

And concrete report creation object will contain the concrete relization of ech
template method