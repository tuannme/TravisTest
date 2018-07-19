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
### ios tests
```
fastlane ios tests
```
test
### ios download_certs
```
fastlane ios download_certs
```
download certs
### ios get_provisioning
```
fastlane ios get_provisioning
```
get provisioning
### ios get_certs
```
fastlane ios get_certs
```
get certificates
### ios build_dev_hockey
```
fastlane ios build_dev_hockey
```
Create a Beta build to Hockey
### ios setup
```
fastlane ios setup
```
Setup
### ios beta
```
fastlane ios beta
```
Build beta

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
