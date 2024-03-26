# Project 0x01. Shell Permissions
This project was carried out during my full-stack software engineering training at [ALX Africa](https://www.alxafrica.com/) and aims to practice shell ownership and privileges commands like su, chown, shmod...

## Technologies
- Script written in bash
- Tested on Ubuntu 20.4
- 
## Files
These files represent the different script files of the project and the description shows what the script does.
| FILES | DESCRIPTION |
| ----------- | ----------- |
| [`0-iam_betty`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/0-iam_betty) | switches the current user to the user betty. The script should be a maximum of 8 characters and we assume the user *betty* exists. |
| [`1-who_am_i`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/1-who_am_i) | Prints the effective username of the current user. |
| [`2-groups`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/2-groups) | Prints all the groups the current user is part of. |
| [`3-new_owner`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/3-new_owner) | Changes the owner of the file *hello* to the user **betty** |
| [`4-empty`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/4-empty) | Creates an empty file called *hello* |
| [`5-execute`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/5-execute) | Add execute permission to the owner of the file *hello* which is in the current directory |
| [`6-multiple_permissions`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/6-multiple_permissions) | adds execute permission to the owner and the group owner, and read permission to other users, to the file *hello* in the working directory |
| [`7-everybody`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/7-everybody) | Add execution permission to the owner, the group owner, and the other users, to the file *hello* which is in the working directory without using a comma in the script |
| [`8-James_Bond`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/8-James_Bond) | sets the permission to the file *hello* as follows:  - Owner: No permission at all - Group: no permission at all - Other users: all the permissions |
| [`9-John_Doe`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/9-John_Doe) | Set the mode of the file  *hello* which is in the working directory to this `- rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`  without using a comma in the script |
| [`10-mirror_permissions`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/10-mirror_permissions) | Sets the mode of the file *hello* the same as *olleh’s* mode. Both files  are in the working directory. |
| [`11-directories_permissions`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/11-directories_permissions) | Add execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users without changing regular files |
| [`12-directory_permissions`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/12-directory_permissions) | Creates a directory called *my_dir* with permissions 751 in the working directory. |
| [`13-change_group`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/13-change_group) | changes the group owner to school for the file *hello* which is in the working directory |
| [`100-change_owner_and_group`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/100-change_owner_and_group) | Change the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory. |
| [`101-symbolic_link_permissions`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/101-symbolic_link_permissions) | Change the owner and the group owner of the symbolic link *_hello* in the working directory to `vincent` and `staff` respectively. |
| [`102-if_only`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/102-if_only) | Change the owner of the file *hello* to `betty` only if it is owned by the user `guillaume`. the file is in the current directory.|
| [`103-Star_Wars`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x01-shell_permissions/103-Star_Wars) | Play the StarWars IV episode in the terminal. |
