## Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

[1.7.0]
---------------------
##### Added
- Check for missing label elements.

##### Changed
- Updated appearances rules with new columns, columns-pack, no-buttons etc.

[1.6.1] - 2019-07-24
---------------------
##### Changed
- Updated form engine and other dependencies.

[1.6.0] - 2019-02-21
---------------------
##### Removed
- Badly broken self-reference check.

[1.5.1] - 2018-12-22
---------------------
##### Fixed
- Installation of this library with `npm install enketo-validate` fails.

[1.5.0] - 2018-12-21
---------------------
##### Added
- Detect disallowed logic references to node itself.
  
#### Changed
- Added version property to CommonJS module validation output.
- Updated to Enketo Core 5.0.x

[1.4.0] - 2018-06-13
--------------------
##### Added
- Version property to CommonJS module.
- Validation for appearances that depend on other appearances.

##### Changed
- Ignore deprecated appearance usage errors in --oc mode.
- No longer providing final 'Valid' or 'Invalid' line in output in --oc mode.

##### Fixed
- Analog-scale appearance outputs warning.
- False error for repeat without ref attribute.

[1.3.0] - 2018-06-07
---------------------
###### Added
- Appearance validation.

###### Changed
- Updated Enketo libraries.

[1.2.2] - 2018-05-01
---------------------
##### Changed
- Updated Enketo libraries.

[1.2.1] - 2018-02-15
---------------------
##### Fixed
- Complex jr:choice-name() calls are not properly ignored causing false errors to be shown.

[1.2.0] - 2018-01-31
---------------------
##### Added
- Custom OC rule for binds with oc:external="clinicaldata".

[1.1.0] - 2018-01-30
---------------------
##### Removed
- Separate OC build

##### Added
- Custom OC rule for external clinical data.
- Rule to require calculations without form control to have readonly="true" attribute.

##### Changed
- The `--oc` flag will now run all OC customizations. No separate build/binary required any more.

[1.0.3] - 2017-01-03
---------------------
##### Changed
- Executable-friendly version of enketo-xslt

##### Fixed
- Cannot build on Windows

[1.0.2] - 2017-12-20
---------------------
##### Changed
- Minor syntax changes.

[1.0.1] - 2017-12-19
---------------------
##### Fixed
- Empty file should output stderr instead of stdout.


[1.0.0] - 2017-12-18
---------------------
##### Added
- First published version. 
