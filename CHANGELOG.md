#Changelog

The versioning in this project is based on [Semantic Versioning](http://semver.org).

## v0.2.0
Introduce a new api to present view controller based errors. This api is especially made for overriding and displaying custom error dialogs, such as [TSMessages](https://github.com/toursprung/TSMessages). The default implementation looks the same as the regular api but is only shown if the passed-in view controller is visible.

## v0.1.2
*There are no changes to the source code in this release. Only the Podfile.lock of the example project has been updated.*

## v0.1.1
- Minor fixes to support travis-ci as continuous integration server
- Reformat the documentation comments to support cocoadocs parsing

## v0.1.0
- Initial release