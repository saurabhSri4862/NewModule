# Uncomment the next line to define a global platform for your project
source 'https://github.com/CocoaPods/Specs'
platform :ios, '11.0'

workspace 'NewModule.xcworkspace'
project 'NewModule.xcodeproj'


#pod 'googleapis', :path => '.'
pod 'OpenTok', '~> 2.14.1'
pod 'AFNetworking', :git => 'https://github.com/kiwipvt/AFNetworking.git', :branch => 'master'
pod 'Fabric', '1.9.0'
pod 'PubNub', :git => 'https://github.com/kiwipvt/objective-c-kiwiup.git', :branch => 'master'
pod 'JSONModel', '1.8.0'
pod 'SSZipArchive', '2.1.1'
pod 'MBProgressHUD', '~> 1.0.0'
pod 'MZTimerLabel', '0.5.4'
pod 'JHChainableAnimations', '~> 1.3.0'
pod 'libPhoneNumber-iOS', '0.9.10'
pod 'AWSS3', '2.4.16'
#pod 'SWTableViewCell', :path => 'DevPods/SWTableViewCell'
pod 'GoogleSignIn', '5.0.2'
pod 'THContactPicker', '~> 2.0'
pod 'Adjust', '~> 4.11.4'
pod 'Branch', '0.30.0'
pod 'Firebase/Core', '6.23.0'
pod 'Firebase/Messaging', '6.23.0'
pod 'Firebase/Auth', '6.23.0'
pod 'FirebaseUI/Phone', '8.4.0'
pod 'GZIP', '~> 1.2'
pod 'TapjoySDK', '12.2.0'
pod 'Firebase/Crashlytics'
pod 'Firebase/Analytics'

def core_pod
    pod 'Core', :path => 'DevPods/Core'
    networking_pod
end

def networking_pod
    pod 'Networking', :path => 'DevPods/Networking'
end

def newmodule_pods
  core_pod
end

target 'Core_Example' do
 project 'DevPods/Core/Example/Core.xcodeproj'
 core_pod
 newmodule_pods
end

target 'Networking_Example' do
 project 'DevPods/Networking/Example/Networking.xcodeproj'
 networking_pod
end

target 'NewModule' do
# Comment the next line if you don't want to use dynamic frameworks
  #use_frameworks!
  pod 'AWSCognito', '2.4.16'
  pod 'SDWebImage', '4.0'
  pod 'SDWebImage/GIF', '4.0.0'
  pod 'MBCircularProgressBar', '0.3.5'
  pod 'AWSDynamoDB', '2.4.16'
  pod 'BCMeshTransformView', '0.9'
  pod 'lottie-ios', '~> 2.1.3'
  pod 'Lightstreamer_iOS_Client', '4.2.1'
  pod 'SnapSDK', '1.3.1', :subspecs => ['SCSDKCreativeKit']
  pod 'Stripe', '18.2.0'
  pod 'TwitterKit', '3.4.2'
  pod 'AppLovinSDK', '6.11.1'
  newmodule_pods
end
