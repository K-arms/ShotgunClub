# Uncomment the next line to define a global platform for your project
 platform :ios, '13.0'

target 'ShotgunClub' do
  use_frameworks!

  pod 'Firebase/Firestore'
  pod 'FirebaseFirestoreSwift'
  pod 'Firebase/Auth'
  pod 'Firebase/Storage'

end

post_install do |installer|
 installer.pods_project.targets.each do |target|
  target.build_configurations.each do |config|
   config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
  end
 end
end