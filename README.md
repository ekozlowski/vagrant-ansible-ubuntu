Vagrant, Ansible and Ubuntu Trusty64 (Virtualbox) Cookiecutter Template
=======================================================================

Usage:

`cookiecutter gh:ekozlowski/vagrant-ansible-ubuntu`

Follow the prompts, and when you get done you'll have a `projectname` (whatever you named your project) directory, that contains all the goodies for running a Vagrant / Ansible / Trusty64 Virtualbox.

Among these goodies:

- a series of .v(x) scripts, which are shortcuts for vagrant commands.  ex: ./vp is short for "vagrant provision", ./vu is short for "vagrant up", ./vr is short for "vagrant destroy -f && vagrant up", etc...
- A Vagrantfile describing a Ubuntu Trusty64 machine provisioned by Ansible
- A very basic Ansible playbook (playbook.yml)
