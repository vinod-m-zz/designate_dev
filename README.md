designate_dev
=============

These scripts are used to setup a Rackspace designate environment. The vagrant file is still under development. The bootstrap.sh file can be used to install successfully.

To run the bootstrap.sh without chef:
``` bash
git clone https://github.com/joeracker/designate_dev.git
vim bootstrap.sh # read it! there are reqs
sudo chmod +x bootstrap.sh #Update permissions
./bootstrap.sh #Execute the script
```

TODO:
* Using vagrant local has issues with some error messages, fix
* The config file should be updated so we are using SED to modify a sample config file instead of overwriting it.
* Need more chef goodness.