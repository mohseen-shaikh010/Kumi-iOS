use_frameworks!
podspec :path => 'Kumi.podspec'

def shared_pods
	pod 'Kumi', :path => './'
	pod 'SwiftLint', '0.29.0'
	pod 'SwiftyJSON', '4.2.0'
end

target 'Kumi' do
	shared_pods
end

target 'KumiTests' do
	shared_pods
end
