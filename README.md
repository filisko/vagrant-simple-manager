# Vagrant Simple Manager

This script provides a simple GUI for Vagrant (for lazy people) that you could use to start, stop, restart and SSH into vagrant machines with your default terminal emulator. Personally, I would recommend you to use this tool if you have more than 5 vagrant machines, if you have 1 or 2 machines there is nearly no difference.

## Download
To download and execute the script simply do the following:
```
wget https://raw.githubusercontent.com/filisko/vagrant-simple-manager/master/vagrant-sm.sh
chmod +x vagrant-sm.sh
./vagrant-sm.sh
```

## Steps

Once you start the script, the main screen that you will see is a list of your current vagrant machines.  
![1. Machines](/images/1.png)

If you select the vagrant machine and then press 'Manage', you will get a list of the available options (only 1 for now) while the vagrant machine is off (see state 'poweroff' on previous image).  
![2. Options off](/images/2.png)

And once you've started the vagrant machine, you will get another list of options (only 3 for now).  
![3. Options off](/images/3.png)


## Suggestions or ideas?

If you have any suggestions, ideas, etc. Create an issue or contact me at: filisfutsarov@gmail.com
