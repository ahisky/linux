Welcome to Androians' Linux Kernel Repository!
```
                                                                 #####
                                                                #######
                   #                                            ##O#O##
  ######          ###                                           #VVVVV#
    ##             #                                          ##  VVV  ##
    ##         ###    ### ####   ###    ###  ##### #####     #          ##
    ##        #  ##    ###    ##  ##     ##    ##   ##      #            ##
    ##       #   ##    ##     ##  ##     ##      ###        #            ###
    ##          ###    ##     ##  ##     ##      ###       QQ#           ##Q
    ##       # ###     ##     ##  ##     ##     ## ##    QQQQQQ#       #QQQQQQ
    ##      ## ### #   ##     ##  ###   ###    ##   ##   QQQQQQQ#     #QQQQQQQ
  ############  ###   ####   ####   #### ### ##### #####   QQQQQ#######QQQQQ
```

What is Linux?
-------------
Please refer to the Linux kernel's README file..

What is this repository?
-------------
This repository stores all the kernel that the ASKY team works on.
This includes the (close to) mainline kernel and the OEM kernel forks for android devices.

Which branch is for what?
-------------
Please refer to the table below.

|Branch|Target|Explanation|
|------|---|---|
|welcome|*|This branch, for explaining how-to|
|torvalds-mainline|*|(Close to) mainline tree|
|ef71-caf|pantech-ef71|CAF Android kernel tree for Pantech EF71 board.|
|ef44-caf|pantech-ef44|CAF Android kernel tree for Pantech EF44 board.|


How to download?
-------------
While you can simply clone the repo, it would download all the kernel sources that you may also not need.
To download the branch that you want, please use this command.

```
$ mkdir Linux_ASKY
$ git clone https://github.com/ahisky/linux.git -b your-branch-name ./Linux_ASKY
Cloning into 'Linux_ASKY'...
remote: Enumerating objects: n, done.
remote: Counting objects: 100% (n/n), done.
...
```
