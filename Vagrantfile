Vagrant.configure("2") do |config|
  config.vm.box = "freebsd/FreeBSD-11.0-RELEASE-p1"
  config.vm.hostname = "freebsd64.io"
  config.vm.base_mac = "0800274EEA6E"
  config.vm.synced_folder ".", "/vagrant", disabled: true
  config.ssh.shell = "/bin/sh"
end
