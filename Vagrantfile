VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  # Use the same key for each machine
  config.ssh.insert_key = false

  config.vm.define "centos7" do |centos7|
    centos7.vm.box = "centos/7"
    centos7.vm.hostname = "centos7"
    centos7.vm.network "private_network", ip: "172.16.0.10", netmask: "255.255.255.0", :name => 'vboxnet0'
    centos7.vm.provider "virtualbox" do |vb|
      vb.name = "centos7.ansible-test.local"
      vb.customize [
        "modifyvm", :id,
        "--groups", "/ansible-test.local",
        "--memory", "512",
        "--cpus", "1"
      ]
    end
  # centos7.vm.provision :ansible do |ansible|
  #   #ansible.ask_vault_pass = true
  #   ansible.compatibility_mode = "2.0"
  #   ansible.playbook = "bootstrap.yml"
  # end
  end

  config.vm.define "centos6" do |centos6|
    centos6.vm.box = "centos/6"
    centos6.vm.hostname = "centos6"
    centos6.vm.network "private_network", ip: "172.16.0.11", netmask: "255.255.255.0", :name => 'vboxnet0'
    centos6.vm.provider "virtualbox" do |vb|
      vb.name = "centos6.ansible-test.local"
      vb.customize [
        "modifyvm", :id,
        "--groups", "/ansible-test.local",
        "--memory", "512",
        "--cpus", "1"
      ]
    end
  # centos6.vm.provision :ansible do |ansible|
  #   #ansible.ask_vault_pass = true
  #   ansible.compatibility_mode = "2.0"
  #   ansible.playbook = "bootstrap.yml"
  # end
  end

  config.vm.define "fedora31" do |fedora31|
    fedora31.vm.box = "fedora/31-cloud-base"
    fedora31.vm.hostname = "fedora31"
    fedora31.vm.network "private_network", ip: "172.16.0.12", netmask: "255.255.255.0", :name => 'vboxnet0'
    fedora31.vm.provider "virtualbox" do |vb|
      vb.name = "fedora31.ansible-test.local"
      vb.customize [
        "modifyvm", :id,
        "--groups", "/ansible-test.local",
        "--memory", "512",
        "--cpus", "1"
      ]
    end
  # fedora31.vm.provision :ansible do |ansible|
  #   #ansible.ask_vault_pass = true
  #   ansible.compatibility_mode = "2.0"
  #   ansible.playbook = "bootstrap.yml"
  # end
  end

  config.vm.define "fedora30" do |fedora30|
    fedora30.vm.box = "fedora/30-cloud-base"
    fedora30.vm.hostname = "fedora30"
    fedora30.vm.network "private_network", ip: "172.16.0.13", netmask: "255.255.255.0", :name => 'vboxnet0'
    fedora30.vm.provider "virtualbox" do |vb|
      vb.name = "fedora30.ansible-test.local"
      vb.customize [
        "modifyvm", :id,
        "--groups", "/ansible-test.local",
        "--memory", "512",
        "--cpus", "1"
      ]
    end
  # fedora31.vm.provision :ansible do |ansible|
  #   #ansible.ask_vault_pass = true
  #   ansible.compatibility_mode = "2.0"
  #   ansible.playbook = "bootstrap.yml"
  # end
  end
    
    config.vm.define "ubuntu1804" do |ubuntu1804|
      ubuntu1804.vm.box = "ubuntu/bionic64"
      ubuntu1804.vm.hostname = "ubuntu1804"
      ubuntu1804.vm.network "private_network", ip: "172.16.0.14", netmask: "255.255.255.0", :name => 'vboxnet0'
      ubuntu1804.vm.provider "virtualbox" do |vb|
        vb.name = "ubuntu1804.ansible-test.local"
        vb.customize [
          "modifyvm", :id,
          "--groups", "/ansible-test.local",
          "--memory", "512",
          "--cpus", "1"
        ]
      end
      # ubuntu1804.vm.provision :ansible do |ansible|
      #   #ansible.ask_vault_pass = true
      #   ansible.compatibility_mode = "2.0"
      #   ansible.playbook = "bootstrap.yml"
      # end
    end

    config.vm.define "ubuntu1604" do |ubuntu1604|
      ubuntu1604.vm.box = "ubuntu/xenial64"
      ubuntu1604.vm.hostname = "ubuntu1604"
      ubuntu1604.vm.network "private_network", ip: "172.16.0.15", netmask: "255.255.255.0", :name => 'vboxnet0'
      ubuntu1604.vm.provider "virtualbox" do |vb|
        vb.name = "ubuntu1604.ansible-test.local"
        vb.customize [
          "modifyvm", :id,
          "--groups", "/ansible-test.local",
          "--memory", "512",
          "--cpus", "1"
        ]
      end
      # ubuntu1604.vm.provision :ansible do |ansible|
      #   #ansible.ask_vault_pass = true
      #   ansible.compatibility_mode = "2.0"
      #   ansible.playbook = "bootstrap.yml"
      # end
    end

    config.vm.define "debian10" do |debian10|
      debian10.vm.box = "debian/buster64"
      debian10.vm.hostname = "debian10"
      debian10.vm.network "private_network", ip: "172.16.0.16", netmask: "255.255.255.0", :name => 'vboxnet0'
      debian10.vm.provider "virtualbox" do |vb|
        vb.name = "debian10.ansible-test.local"
        vb.customize [
          "modifyvm", :id,
          "--groups", "/ansible-test.local",
          "--memory", "512",
          "--cpus", "1"
        ]
      end
      # debian10.vm.provision :ansible do |ansible|
      #   #ansible.ask_vault_pass = true
      #   ansible.compatibility_mode = "2.0"
      #   ansible.playbook = "bootstrap.yml"
      # end
    end

    config.vm.define "debian9" do |debian9|
      debian9.vm.box = "debian/stretch64"
      debian9.vm.hostname = "debian9"
      debian9.vm.network "private_network", ip: "172.16.0.17", netmask: "255.255.255.0", :name => 'vboxnet0'
      debian9.vm.provider "virtualbox" do |vb|
        vb.name = "debian9.ansible-test.local"
        vb.customize [
          "modifyvm", :id,
          "--groups", "/ansible-test.local",
          "--memory", "512",
          "--cpus", "1"
        ]
      end
      # debian9.vm.provision :ansible do |ansible|
      #   #ansible.ask_vault_pass = true
      #   ansible.compatibility_mode = "2.0"
      #   ansible.playbook = "bootstrap.yml"
      # end
    end
end
