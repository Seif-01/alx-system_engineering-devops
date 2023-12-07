# 0x01. Shell, permissions
                          by seif-01

This repository contains shell scripts for various tasks related to file permissions and user management in Unix-like operating systems. Below is a list of scripts along with their functionalities:

## Task 0: I Am Betty
- File: `0-iam_betty`
- Description: A script that switches the current user to the user `betty`.

## Task 1: Who Am I
- File: `1-who_am_i`
- Description: A script that prints the effective username of the current user.

## Task 2: Groups
- File: `2-groups`
- Description: A script that prints all the groups the current user is part of.

## Task 3: New Owner
- File: `3-new_owner`
- Description: A script that changes the owner of the file `hello` to the user `betty`.

## Task 4: Empty!
- File: `4-empty`
- Description: A script that creates an empty file called `hello`.

## Task 5: Execute
- File: `5-execute`
- Description: A script that adds execute permission to the owner of the file `hello`.

## Task 6: Multiple Permissions
- File: `6-multiple_permissions`
- Description: A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

## Task 7: Everybody!
- File: `7-everybody`
- Description: A script that adds execution permission to the owner, the group owner, and the other users, to the file `hello`.

## Task 8: James Bond
- File: `8-James_Bond`
- Description: A script that sets the permission to the file `hello` as owner: no permission, group: no permission, other users: all permissions.

## Task 9: John Doe
- File: `9-John_Doe`
- Description: A script that sets the mode of the file `hello` to `-rwxr-x-wx`.

## Task 10: Look in the Mirror
- File: `10-mirror_permissions`
- Description: A script that sets the mode of the file `hello` the same as `olleh`'s mode.

## Task 11: Directories
- File: `11-directories_permissions`
- Description: A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.

## Task 12: More Directories
- File: `12-directory_permissions`
- Description: A script that creates a directory called `my_dir` with permissions `751` in the working directory.

## Task 13: Change Group
- File: `13-change_group`
- Description: A script that changes the group owner to `school` for the file `hello`.

## Task 14: Owner and Group
- File: `100-change_owner_and_group`
- Description: A script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

## Task 15: Symbolic Links
- File: `101-symbolic_link_permissions`
- Description: A script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively. `_hello` is a symbolic link.

## Task 16: If Only
- File: `102-if_only`
- Description: A script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

## Task 17: Star Wars
- File: `103-Star_War`
- Description: A script that plays the Star Wars IV episode in the terminal.

Feel free to use these scripts for managing file permissions and user-related operations in Unix-like systems.

