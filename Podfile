# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

target 'Flash Chat' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Flash Chat
pod 'Firebase'
pod 'Firebase/Auth'
pod 'Firebase/Database'
pod 'ChameleonFramework'
pod 'SVProgressHUD'
end


post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
            config.build_settings['SWIFT_VERSION'] = '3.0'
            config.build_settings['MACOSX_DEPLOYMENT_TARGET'] = '10.10'
        end
    end
end
