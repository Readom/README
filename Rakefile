# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'LetsBeRandom'

  app.deployment_target = '9.2'
  app.device_family = [:iphone]
  app.identifier = 'com.liulantao.LetsBeRandom'

  app.prerendered_icon = false
  app.sdk_version = '9.2'
  app.version = '1.0.0'

  app.development do
    app.provisioning_profile = 'mobileprovision/LetsBeRandom_Development.mobileprovision'
  end
end
