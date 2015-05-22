# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/android'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'BluePotion'
  app.package = "com.infinitered.bluepotion"
  app.application_class = "BluepotionApplication"
  app.theme = "@android:style/Theme.Holo.Light"
  #app.permissions = [:internet, :access_network_state, :access_coarse_location, :access_fine_location, :write_external_storage]
  #app.version_name = "0.0.2"
  app.icon = 'ic_launcher'

  app.api_version = "16"
  app.development { app.archs << "x86" } # for genymotion support

  app.main_activity = "PMHomeActivity"
  app.sub_activities += %w(PMSingleFragmentActivity)
end
