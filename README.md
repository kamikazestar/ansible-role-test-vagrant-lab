# Vagrant Lab Series: Ansible role test

This Vagrant lab will provision VirtualBox based VM's that can be use to test Ansible roles locally.
List of the supported Linux distributions:

- CentOS 7
- CentOS 6
- Fedora 31
- Fedora 30
- Ubuntu 18.04
- Ubuntu 16.04
- Debian 10
- Debian 9

## Requirements

To run this lab properly you need to have:

- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)

Each VM is had been configured to use 512MB of RAM memory which can be an issue on devices with 8GB or less of the RAM memory. This could easly changed by changing RAM memory assigment for each of the VM to i.e. 256MB of RAM memory.

## Dependencies

This lab deppends on this Vagrant boxes:

- [CentOS 7](https://app.vagrantup.com/centos/boxes/7)
- [CentOS 6](https://app.vagrantup.com/centos/boxes/6)
- [Fedora 31](https://app.vagrantup.com/fedora/boxes/31-cloud-base)
- [Fedora 30](https://app.vagrantup.com/fedora/boxes/30-cloud-base)
- [Ubuntu 18.04](https://app.vagrantup.com/ubuntu/boxes/bionic64)
- [Ubuntu 16.04](https://app.vagrantup.com/ubuntu/boxes/xenial64)
- [Debian 10](https://app.vagrantup.com/debian/boxes/buster64)
- [Debian 9](https://app.vagrantup.com/debian/boxes/stretch64)

## License

This project is licensed under the GPL License 3.0 - see the [LICENSE](https://github.com/kamikazestar/ansible-role-test-vagrant-lab/blob/master/LICENSE) for details.

## Author Information

* **Marcin Slabonski** - *Initial work* - [kamikazestar](https://github.com/kamikazestar)