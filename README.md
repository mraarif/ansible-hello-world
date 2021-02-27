# ansible-hello-world

A collection of ansible playbooks with a very basic setup and tasks intended to be used as a reference.
following playbooks are available:

- [apache-installation](/apache-installation)

### How to run

make sure `ansible` is installed, if not run: (for macOS), you can follow installation guide
[here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) for other platforms.

```
brew install ansible
```

update the [inventory.txt](/apache-installation/inventory.txt) to add your host.

and run:

```
ansible-playbook -i inventory.txt main.yml --private-key your-private-key.pem
```
