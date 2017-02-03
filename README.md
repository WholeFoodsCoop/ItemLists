# Item Lists
Simple, attribute-based lists of item identifiers

## Current Lists
* **organic.csv** is a list of known certified organic items. This is a US-centric list and generally means USDA certified but may include some OCIA items too
* **fairtrade.csv** is a list of known fair trade items. No specific certification standard is used here. Any item that makes a fair trade claim on its packaging can go on the list.

## List Format
Lists are provided as two column CSV files. The first column is the UPC or EAN without check digit. The second column is the same UPC or EAN with check digit. Both values will be zero padded so the first column is always 13 digits and the second is always 14 digits.

## What Can I Do With These Lists?
Whatever you want.

## Contributing
If you want to add identifiers to a list, make a pull request.
