# helloVM
### VirtualEnviroment for the [helloAHworld project](https://github.com/MaGaMeGa/helloAHworld)


Dowload links for the hellowAHworld virtual machine:

- https://mega.nz/file/aFgR2aiT#BO7gQ81Ixw71G0-CIZIc5wbQxc0jZ-BpFx1P4xsUVIw
- https://ufile.io/u49n2tbb

_Verifications_

MD5 hash of HELLO_AH_WORLD.ova:<br />
3b145385ad2c57e5e75041d89528f0ba

SHA512 hash of HELLO_AH_WORLD.ova:<br />
34412d82457c9890ebd1ae08c46ad7ed5e98500b68d6b738577bdfe1379c8cbced124ec28776670cc2bc63c6cccc1e7e2696e74b3632b2cce8a8426b09804b72

#### Prerequisites
Make sure you installed VirtualBox,<br />
and that VirtualBox installation folder is added to the *system* (not the user) PATH environment variable.<br />

###### VirtualBox installation: <br />
- [OFFICAL GUIDE](https://www.virtualbox.org/manual/UserManual.html#installation) <br />
- [An other guide](https://www.wikihow.com/Install-VirtualBox) <br />
###### Set Path:  <br />
- [SET PATH LINK WINDOWS 10](https://www.alphr.com/environment-variables-windows-10/)
 
#### How to use
Download the  virtual machine. (1.6 G - may take some time... )<br />

Open terminal/command line etc. and run:<br />
```bash
vboxmanage import HELLO_AH_WORLD.ova
vboxmanage startvm HELLO_AH_WORLD
```

Once the Virtual Machine boots,<br />
log in as :<br />
```bash
root
```
with password: <br />
```bash
default arrowhead password
```

run: <br />
```bash
cd /home/ah/tests/clienttests && ./run_client_tests.sh
```
