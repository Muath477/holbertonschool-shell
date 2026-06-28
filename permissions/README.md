# Permissions

This folder contains shell scripts about Linux permissions.

- `0-iam_betty`: Switches the current user to the user betty.
- `1-who_am_i`: Prints the effective username of the current user.
- `2-groups`: Prints all the groups the current user is part of.
- `3-new_owner`: Changes the owner of the file hello to the user betty.
- `4-empty`: Creates an empty file called hello.
- `5-execute`: Adds execute permission to the owner of the file hello.
- `6-multiple_permissions`: Adds execute permission to owner and group, and read permission to others, for the file hello.
- `7-everybody`: Adds execute permission to the owner, group, and other users for the file hello.
- `8-James_Bond`: Sets permissions so that only other users have all permissions on the file hello.
- `9-John_Doe`: Sets the mode of the file hello to -rwxr-x-wx (753).
- `10-mirror_permissions`: Sets the mode of the file hello to be the same as the mode of the file olleh.
- `11-directories_permissions`: Adds execute permission to all subdirectories of the current directory for owner, group, and others.
- `12-directory_permissions`: Creates a directory called my_dir with permissions 751.
