# ansible-iptables-example

This is a code from [here](https://weastur.medium.com/setting-up-the-iptables-with-ansible-66d0be5c286d)

## Run

1. Install ansible.
1. Fix inventory
1. Run `ansible all -m include_role -a name=firewall --become`
