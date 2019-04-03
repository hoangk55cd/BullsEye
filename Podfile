# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def podCollection
  pod 'SwiftyJSON'
  pod 'IQKeyboardManagerSwift'
  pod 'Dynatrace'
end

target 'BullsEye' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  podCollection
  
  # Pods for BullsEye
  
  target 'BullsEyeMockTests' do
    inherit! :search_paths
    # Pods for testing
    podCollection
  end

  target 'BullsEyeTests' do
    inherit! :search_paths
    # Pods for testing
    podCollection
  end

  target 'BullsEyeUITests' do
    inherit! :search_paths
    # Pods for testing
    podCollection
  end

end
