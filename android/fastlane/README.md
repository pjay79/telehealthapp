fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android bump_version_code
```
fastlane android bump_version_code
```

### android dev
```
fastlane android dev
```
Deploy a new Dev version to Google Play
### android qa
```
fastlane android qa
```
Deploy a new QA version to Google Play
### android prod
```
fastlane android prod
```
Deploy a new Prod version to Google Play

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
