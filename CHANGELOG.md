# OpenStudio Model Articulation Gems

## Version 0.2.0

* Support for OpenStudio 3.0
    * Upgrade Bundler to 2.1.x
    * Restrict to Ruby ~> 2.5.0   
    * Removed simplecov forked dependency 
* Upgraded openstudio-extension to 0.2.3
    * Updated measure tester to 0.2.0 (removes need for github gem in downstream projects)
* Upgraded openstudio-standards to 0.2.11
* Exclude measure tests from being released with the gem (reduces the size of the installed gem significantly)
* Removed dependency on openstudio-common-measures gem

## Version 0.1.1

* Update to OpenStudio Common Gem 0.1.2 (and extension gem 0.1.6)
* Merge in OpenStudio articulation measures from OpenStudio-measures
* Code cleanup on the measures
* Update copyrights and licenses 

## Version 0.1.0

* Initial release of the articulation measures that are used for generating OpenStudio models.
