# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
workspace 'TestFrameWork'
project 'TestFrameWork.xcodeproj'
project 'CallingFrameWork/CallingFrameWork.xcodeproj'

target 'TestFrameWork' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  project 'TestFrameWork.xcodeproj'

  # Pods for TestFrameWork

pod 'SDWebImage'
end

target 'CallingFrameWork'do
  use_frameworks!
  project 'CallingFrameWork/CallingFrameWork.xcodeproj'
  pod 'Alamofire', '~> 4.7.3'
end
