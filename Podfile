# Uncomment the next line to define a global platform for your project
# platform :ios, '10.0'

$BRANCH = 'develop'

$CGM_CORE_PATH = { :git => "https://github.com/dexcom-inc/iOS_CGM_Core.git", :branch => 'DSDK-8511-create-github-repos'}

#$CGM_CORE_PATH = { :path => "../../Repoes/iOS_CGM_Core"}


target 'MyDexcomApp' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for MyDexcomApp
    
    pod 'CGMCore/PublicAPI',    $CGM_CORE_PATH

end
