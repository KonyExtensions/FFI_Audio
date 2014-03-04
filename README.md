Audio FFIs
==========

Foreign Function Interfaces for Kony Development


This FFI does Audio Recording and other operations like 1. Play 2.Stop 3.Pause . Also it does a cleaning/purging of the recoded data on an explicit call.Add AVFoundation framework in your Xcode project before building the APK.At time of development "prepareToRecord" function must be invoked before you start invoking any other function.You should pass a a file name "yourFileName.mp4" to the prepareToRecord function, and mp4 was the format with which the audio quality was experienced better.

It also have an option to upload the recorded audio files to an AWS S3 bucket but it only for iOS and Android.
For this you have to add the AWS frameworks added in this project.
