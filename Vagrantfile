Vagrant.configure("2") do |config|
  config.vm.define "server1" do |server1|
    server1.vm.box = "ubuntu/bionic64"
    server1.vm.network "forwarded_port", guest: 22, host: 2221
  end

  config.vm.define "server2" do |server2|
    server2.vm.box = "ubuntu/bionic64"
    server2.vm.network "forwarded_port", guest: 22, host: 2223
  end

  config.vm.define "server3" do |server3|
    server3.vm.box = "ubuntu/bionic64"
    server3.vm.network "forwarded_port", guest: 22, host: 2224
  end
end
