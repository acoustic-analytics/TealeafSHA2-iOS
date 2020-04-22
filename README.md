# TealeafSHA2

TealeafSHA2 is a shared utility library used by Acoustic, L.P. DigitalAnalytics and Tealeaf iOS SDKs.


## Getting Started

### Prerequisites

You need to have recent cocoapods version installed on your Mac OS. Current version is 1.6.1. Please refer to cocoapods website for the details.

### Installing

You do not need to use TealeafSHA2 directly. Tealeaf and DigitalAnalytics dependencies are set in such a way that appropriate version of EOCore library will be automatically downloaded and integrated into your iOS project when you refer to those SDKs from your Podfile.

## Troubleshooting

If you are using Debug version of TealeafSHA2. i.e. pod TealeafSHA2Debug used by pods IBMTealeafDebug and DigitalAnalyticsDebug, then you may edit your project's scheme in XCode and add environmental variable EODebug and set its value to 1. This will make EOCore to start writing debug logs to your xcode console window. If and when you want to report issues, the DigitalAnalytics and Tealeaf support engineers will ask you for these logs.


## Used By

* [DigitalAnalytics](https://github.com/ibm-watson-cxa/DigitalAnalytics) - Acoustic, L.P. Digital Analytics SDK
* [Tealeaf](https://github.com/ibm-watson-cxa/IBMTealeaf) - Acoustic, L.P. Experience Analytics SDK


## License

License files can be read [here](https://github.com/ibm-watson-cxa/TealeafSHA2-iOS/tree/master/Licenses)

