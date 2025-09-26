# Permissions Scripts

This folder contains 17 files:

- 0-iam_betty: switches the current user to betty
- 1-who_am_i: prints the effective username
- 2-groups: prints all groups the current user is part of
- 3-new_owner: changes owner of 'hello' to betty
- 4-empty: creates an empty file 'hello'
- 5-execute: adds execute permission to owner of 'hello'
- 6-multiple_permissions: adds execute to owner/group, read to others for 'hello'
- 7-everybody: adds execute permission for all users to 'hello'
- 8-James_Bond: sets 'hello' permissions to 007
- 9-John_Doe: sets 'hello' permissions to 753
- 10-mirror_permissions: mirrors permissions of 'olleh' to 'hello'
- 11-directories_permissions: adds execute to all subdirectories
- 12-directory_permissions: creates directory 'my_dir' with 751
- 13-change_group: changes group of 'hello' to 'school'
- 14-change_owner_and_group: changes owner to vincent, group to staff for all files
- 15-symbolic_link_permissions: changes owner/group of _hello symlink to vincent/staff
- 16-if_only: changes owner of 'hello' to vincent if current owner is guillaume

