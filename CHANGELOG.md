# Changelog

#### v0.3.1
- `Added` Added `+contain`, `+cover`, `+h-fill` and `+v-fill` utilities
- `Improved` Fitted bars now target only at certain breakpoints, instead of cascading
- `Fixed` Fixed bug where unprefixed quotes mixin couldn't accept content

#### v0.3.0

- `Added` Added absolute/relative unit detection functions to public core API
- `Added` Added transition management (setting and function) to the extra API
- `Added` Added unprefixed structure mixins (structure, alignbox, ratiobox)
- `Improved` Improved label positioning by bypassing some unnecessary calculations
- `Improved` Gutter function will now return a number instead of a list when only one gutter is requested

#### v0.2.0
- `Added` Added new spacer utility to horizontally and vertically space an elements children
- `Added` Added new responsive mixin "sl-properties"
- `Added` Added alignbox group feature to allow multiple alignments in one alignbox
- `Improved` Gutter setting now allows lists of gutter values, that target individual sides
- `Improved` Ratiobox now allows width/max-width to be set
- `Improved` Improved error reporting in various cases
- `Improved` Setting the font variable now allows space-separated font names
- `Improved` Removed default browser appearance on fields and buttons
- `Fixed` Fixed bug with textbox elements (field, button, etc) when setting line height
- `Fixed` Fixed bug with "sl-sum" function where cases of supplying just zero values threw an error
- `Fixed` Corrected issue with the horizontal outer gaps on fitted bars not displaying correctly
- `Fixed` Fixed the name of the prefixless float label mixin
- `Fixed` Fixed class names of column responsive sizes
- `Fixed` Fixed issue with ratiobox mixin not applying styles correctly

#### v0.1.0
- `Added` Added tests and linting
- `Added` Added CI support
- `Added` Created opt-in unprefixed versions of functions and mixins
- `Improved` Added more and improved docstrings across codebase
- `Improved` Renamed the "theme" API to "extra" as the old name was misleading
- `Improved` Moved the icon module to the extra section as it fits better there
- `Fixed` Removed the focus+hover outline removal as this resulted in unwanted behaviour

#### v0.0.1
- Initial release
