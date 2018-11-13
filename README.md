### Virtual Machine
- Vagrant: https://www.vagrantup.com/docs/installation/
- Centos 7: https://blog.centos.org/2018/04/updated-centos-vagrant-images-available-v1803-01/
- Vagrant Vbguest plugin: https://github.com/dotless-de/vagrant-vbguest, this plugin will run as middleware to install/update the VirtualBoxGuest Addition
- Update kernal if vbguest installation failed: https://www.megajason.com/2017/06/10/install-virtualbox-guest-additions-on-centos-7/

### Jupyter with Multiple environment
- run "jupyter kernelspec list" to check the current installed kernels
- Add a new kernel linked to given virtual environment
  - create new folder with kernel.json file, in the json file set 'arg' as the path to your virtual environemnt python
  - run 'jupyter kernelspec install <new_kernel_path>'


