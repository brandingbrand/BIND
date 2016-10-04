# Uncomment this line to define a global platform for your project
# platform :ios, '6.0'

source 'https://github.com/CocoaPods/Specs.git'

workspace 'BIND'

target 'BIND' do
    platform :ios, '7.0'
    xcodeproj 'BIND.xcodeproj'
	pod 'libextobjc'
    pod 'BB-NODE_', :git => 'https://github.com/brandingbrand/NODE.git', :tag => '0.1.2'
end

target 'BIND-OSX' do
    platform :osx, '10.9'
    xcodeproj 'BIND.xcodeproj'
    pod 'libextobjc'
end

target 'BINDTests' do
    platform :ios, '7.0'
    xcodeproj 'BIND.xcodeproj'
    pod 'Kiwi'
end

target 'BIND-OSXTests' do
    platform :osx, '10.9'
    xcodeproj 'BIND.xcodeproj'
    pod 'Kiwi'
end

target 'BINDAppTests' do
    platform :ios, '7.0'
    xcodeproj 'BIND.xcodeproj'
    pod 'Kiwi'
end

target 'BINDPlugin' do
    platform :osx, '10.9'
    xcodeproj 'BINDPlugin/BINDPlugin.xcodeproj'
    pod 'XcodeEditor'
end

target 'BINDPluginTests' do
    platform :osx, '10.9'
    xcodeproj 'BINDPlugin/BINDPlugin.xcodeproj'
    pod 'Kiwi'
end
