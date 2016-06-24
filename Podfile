source 'https://github.com/CocoaPods/Specs.git'

use_frameworks!

def common
    pod 'Alamofire', '~> 3.4'
    pod 'RxSwift', '~> 2.5.0'
    pod 'RxCocoa', '~> 2.5.0'
end

target 'RxAlamofireExample' do
    platform :ios, '8.0'
    common
end

target 'RxAlamofiretvOSExample' do
    platform :tvos, '9.0'
    common
end

target 'RxAlamofire-iOS' do
   common

   target 'RxAlamofireTests' do
       pod 'OHHTTPStubs'
       pod 'OHHTTPStubs/Swift'
       pod 'RxBlocking'
   end
end
