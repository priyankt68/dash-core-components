# Change Log for dash-core-components
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [0.5.3] - 2017-07-03
### Added
- A `range` object is now included in the `selectedData` object that specifies
  that dimensions of the selected region.
- A `lassoPoints` object is now included in the `selectedData` object that
  provides coordinates of the lassoed region.

## [0.5.2] - 2017-07-03
### Added
- A new property `clear_on_unhover` on the `Graph` component will clear the
  `hoverData` property when the user "unhovers" from a point if True. If False,
  then the `hoverData` property will be equal to the data from the last point
  that was hovered over. The default is False.
