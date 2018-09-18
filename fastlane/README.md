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
## iOS
### ios setup_anka
```
fastlane ios setup_anka
```
Lane to setup Anka VM for CI
### ios cleanup_anka
```
fastlane ios cleanup_anka
```
Lane to cleanup Anka VM after CI
### ios anka_test
```
fastlane ios anka_test
```
Lane to run tests in Anka
### ios test
```
fastlane ios test
```
Lane to run tests

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
