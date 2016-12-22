Vagrant.configure("2") do |config|
  config.vm.box = "freebsd/FreeBSD-11.0-RELEASE-p1"
  config.vm.hostname = "freebsd64.io"
  config.vm.base_mac = "0800274EEA6E"
  config.vm.synced_folder ".", "/vagrant", disabled: true
  config.vm.network "forwarded_port", guest: 3306, host: 3306, host_ip: "127.0.0.1"
  config.ssh.shell = "/bin/sh"
end
