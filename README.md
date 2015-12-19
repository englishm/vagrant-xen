# Vagrant Xen

Ubuntu 14.04 Vagrant basebox for Xen unikernel development

Pre-build basebox available as [englishm/ubuntu-14.04-xen][]

Based on <https://github.com/mirage/mirage-vagrant-vms>

## Usage

- `vagrant init englishm/ubuntu-14.04-xen`
- `vagrant up`

Note: virtualbox filesystem sharing (e.g. mounting `$PWD` at `/vagrant`) is disabled by default for this basebox.
If you need shares, add them to your `Vagrantfile` using another driver (e.g. `nfs`).

[englishm/ubuntu-14.04-xen]: https://atlas.hashicorp.com/englishm/boxes/ubuntu-14.04-xen/versions/0.0.1/
