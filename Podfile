# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

source 'https://github.com/CocoaPods/Specs.git'
target 'webRtcWatch' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  platform :ios, '9.0'

  # Pods for webRtcWatch
　pod 'GoogleWebRTC'
  pod 'Starscream'
  pod 'SwiftyJSON'

  post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
      config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
    end
  end

end

target 'webRtcWatch WatchKit App' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for webRtcWatch WatchKit App

end

target 'webRtcWatch WatchKit Extension' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for webRtcWatch WatchKit Extension

end
