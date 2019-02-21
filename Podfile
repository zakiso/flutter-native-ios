platform :ios, '8.0'
use_frameworks!

target 'FlutterNativeiOS' do
  pod 'AFNetworking', '~> 2.6'
end

flutter_application_path = './flutter-module-demo/'
eval(File.read(File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')), binding)
