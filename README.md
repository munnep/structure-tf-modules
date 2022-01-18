# structure_tf_modules_test

This repo has a vagrant box to easily use for testing this repository [https://github.com/kikitux/structure-tf-modules#readme](https://github.com/kikitux/structure-tf-modules#readme)

You can then run the repo script to have a structure create to use as a template for your environment. 

Vagrant virtual machine:
- ubuntu virtual machine starts
- terraform installed
- ruby and bundle get installed
- repository ```kikitux/structure-tf-modules``` gets cloned


# Prerequisites

Vagrant [See documentation](https://www.vagrantup.com/docs/installation)  
Virtualbox [See documentation](https://www.virtualbox.org/wiki/Downloads)

# Use the nothing_module_test

- Clone the repository to your local machine
```
git clone https://github.com/munnep/structure_tf_modules_test.git
```

- Change your directory
```
cd structure_tf_modules_test
```

- Start a virtual machine with Vagrant
```
vagrant up
```

- ssh into the virtual machine with Vagrant.
```
vagrant ssh
```

- go to the directory ```/vagrant/structure-tf-modules/```
```
cd /vagrant/structure-tf-modules/
```

- Run the script to create an example directory structure
``` 
./structure.sh     
```

- exit out of the vagrant machine
```
exit
```

- destroy the vagrant machine
```
vagrant destroy
```