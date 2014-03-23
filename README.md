# ansible-role-daemontools

  Install daemontools and wait reboot (if newly installed)

## Supported OS

* Ubuntu (only 12.04 tested)

## vagrant notes

If you use this role with vagrant, you need to set private network in Vagrantfile.

```ruby
config.vm.network "private_network", ip: "192.168.111.222"
```

Otherwise, your ansible will wait reboot forever.
