# Release v3.2 (2015-01-04)

* Added support for non-ASCII characters.
* Modified notifications to be more streamlined.

# Release v3.1 (2014-12-29)

* Entirely new settings/configuration management via `lpsettings`.
* Added ability to login to LastPass.
* Added ability to logout from LastPass.
* Added ability to configure filepath to `lpass`.
* Added new (and slimmer) icons.
* Environment-proofed Python path in all scripts and Script Filters.

# Release v3.0 (2014-12-29)

* Shifted from Ruby to Python.
* Implemented [Alfred-Workflow](https://github.com/deanishe/alfred-workflow) (including fuzzy search, configuration management, and more).
* Added `lpbrowser` command to look up default browser's front-most tab's URL in the vault.
* Configuration management: cache timeout, default browser, number of generated password, and generated password length.
* Check for whether `lpass` is logged in.

# Release v2.0 (2014-12-16)

* Added data caching
* Added command to force data caching
* Added ability to specify path to `lpass` executable
* Added fallback lookup for `lpass` executable
* Changed `lpvs` command to look at vault item name *and* URL
* Major code refactoring

# Release v1.0 (2014-12-16)

* Added ability to search a LastPass vault.
* Added ability to launch URL of LastPass item.
* Added ability to copy username of LastPass item.
* Added ability to copy password of LastPass item.
* Added ability to generate a random password.
* Created documentation.
