# vagrant-fifo Vagrant plugin

vagrant-fifo is a Vagrant provider for Project-Fifo

Note: this is under development and is probably broken. Patches welcome.

## Installation

    $ https://github.com/bakins/vagrant-fifo.git
    $ cd vagrant-fifo
    $ gem build vagrant-fifo.gemspec ; 
    $ vagrant plugin install vagrant-fifo-0.2.1.gem 
    $ vagrant box add dummy ./dummy.box

## Usage

Check out a chef-repo with a Fifo compatible Vagrantfile, then run "vagrant up"

    $ vagrant up --provider=fifo
    $ vagrant provision
    $ vagrant ssh
    $ vagrant destroy

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Thanks

Based on [vagrant-joyent](https://github.com/someara/vagrant-joyent)

## License
Apache 2
