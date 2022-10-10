## Instructions to set up your VMs:

For windows users make sure you have git bash installed. If you don't, here is the download link: https://git-scm.com/downloads

For mac users, you will just use terminal which already on your systems

Everyone should have Virtual box installed. If you do not, here is the link: [VirtualBox Download Site](https://www.virtualbox.org/wiki/Downloads)

Download vagrant itself if you have not done so: [Vagrant program](https://www.vagrantup.com/docs/providers/virtualbox)

- This vagrant program does not need to be opened once you install it. If you attempt to open the vagrant program itself, it will just open then close a terminal.


Download these two files: [vagrantfile installer script](vagrant-linux.sh) and (Vagrantfile)

When you go to each page, download using the icon on the right side that has a down arrow.

Once all of the above is downloaded and/or installed, open up git bash/terminal and use this command to navigate to your downloads folder as this should be where the vagrant files are: cd ~/Downloads

Download these two files: [vagrantfile installer script](vagrant-linux.sh) and [Vagrantfile](Vagrantfile)

When you go to each page, download using the icon on the right side that has a down arrow.

Once all of the above is downloaded and/or installed, open up git bash/terminal and use this command to navigate to your downloads folder as this should be where the vagrant files are: `cd ~/Downloads`


Once in Downloads run this command:

- Git Bash (windows): `bash vagrant-linux.sh --create`
- Terminal(mac): `sudo bash vagrant-linux.sh --create`

This process is will take a bit of time depending on your internet connection will take some time.

Once the `--create` command finishes, virtual box should have opened up and your VM should be starting up, if not already.


## Maintaining your VM:

From time to time the VM might crap out (rarely though) but updating the VM through vagrant will fix most issues. You should typically update your VM every week to 2 weeks to make sure you have the most up to date version. That the vagrant create command created:

- `cd ~/Documents/Cybersecurity-Bootcamp/Linux-Module`
- `vagrant box update`
- `vagrant destroy`
- `vagrant up`
- `vagrant box prune (optional)`


By the time vagrant up finishes your VM will/should be up and starting.

**CREDENTIALS TO GET INTO YOUR VM**: `sysadmin:cybersecurity`

Then to access your VM, just open VirtualBox and you should see it there.


