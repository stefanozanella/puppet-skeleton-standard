# -*- mode: ruby -*-
# vi: set ft=ruby :

notification :off

guard 'rake' :task => :test do
  watch(%r{^(manifests|spec)\/(.+)\.pp$})
end
