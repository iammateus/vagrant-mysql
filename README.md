# vagrant-mysql

A MySQL vagrant machine with external connectivity to the host machine.

## Requeriments

1. [Vagrant](https://www.vagrantup.com/).
2. [A provider](https://www.vagrantup.com/docs/providers).

## Installation

    $ vagrant up
    
## How to connect externally

    $ mysql -h 127.0.0.1 -P 3306 -u {USER} -p 

## MySQL users

| User | Password | Connectivity |
|--|--|--|
| root| root | local |
| mateus| mateus | local and external |

## License

[MIT](https://github.com/iammateus/vagrant-mysql/blob/main/LICENSE)
