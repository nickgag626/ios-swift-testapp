#!/usr/bin/ruby

use_frameworks!
platform :ios, "11.0"
inhibit_all_warnings!

target 'the-example-app.swift' do
  pod 'Contentful', '~> 5.1.2'
  pod 'FirebaseCore'
  pod 'FirebaseAnalytics'
  pod 'SnowplowTracker'
  pod 'markymark'
  pod 'AlamofireImage'
  pod 'DeepLinkKit'
  pod 'Fabric'
  pod 'Crashlytics'

  target 'the-example-app.swiftTests' do
    inherit! :search_paths
    pod 'Nimble'
    pod 'KIF'
    # Firebase has an issue with Xcode 10 and must be included in test target
    # https://stackoverflow.com/questions/38216090/xcode-unit-testing-with-cocoapods
    pod 'Firebase'
    

  end
end

