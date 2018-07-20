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
### ios download_certs
```
fastlane ios download_certs
```
Download certificates and provisioning profiles
### ios build_dev
```
fastlane ios build_dev
```
Create a Beta build
### ios submit_hockey
```
fastlane ios submit_hockey
```
Submit to Hockey
### ios beta
```
fastlane ios beta
```
Build beta

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
