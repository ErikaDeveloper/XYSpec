use_frameworks!

platform :ios, '8.0'

target 'pod_test_Example' do
  pod 'pod_test', :path => '../'

  target 'pod_test_Tests' do
    inherit! :search_paths

    pod 'Specta'
    pod 'Expecta'
    pod 'FBSnapshotTestCase'
    pod 'Expecta+Snapshots'
  end
end
