
Vagrant.configure("2") do |config|
  config.vm.box = "geerlingguy/ubuntu1604"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "main.yml"
  end

  
end