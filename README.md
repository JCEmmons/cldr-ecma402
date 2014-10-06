# cldr-ecma402 

This project provides CLDR data in JSON format for use with the ecma402 project at git://github.com/ibm-js/ecma402.git
The data contains keys that are fully compatible with the CLDR JSON specification at http://cldr.unicode.org/index/cldr-spec/json
and has the identical keys and structure as the JSON published as part of the CLDR project. The primary difference
is that the JSON in this package has been filtered to contain only those fields that are actually used by the ecma402
implementation.

## Status
Based on CLDR Release 26.0 published 2014-09-18 ( //http://cldr.unicode.org/index/downloads )

## Licensing

This project is distributed under the Unicode license agreement. (./LICENSE).

## Dependencies

[![Dependency Status](https://david-dm.org/ibm-js/cldr-ecma402.png)](https://david-dm.org/ibm-js/cldr-ecma402)

None

## Installation

_Bower_ release installation:

    $ bower install cldr-ecma402

_Manual_ master installation:

    $ git clone git://github.com/ibm-js/cldr-ecma402.git

## Documentation

For further documentation on how to build the JSON data using the CLDR tools, refer to the 
[![configuration README](config/README.md)].
