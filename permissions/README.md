# Shell Permissions

This project covers Linux file permissions using bash scripts.

## Scripts

| File | Description |
|------|-------------|
| `0-iam_betty` | Switches current user to betty |
| `1-who_am_i` | Prints the effective username of the current user |
| `2-groups` | Prints all groups the current user belongs to |
| `3-new_owner` | Changes the owner of file hello to betty |
| `4-empty` | Creates an empty file called hello |
| `5-execute` | Adds execute permission to the owner of hello |
| `6-multiple_permissions` | Adds execute to owner/group, read to others on hello |
| `7-everybody` | Adds execute permission to owner, group and others on hello |
| `8-James_Bond` | Sets hello permissions: no perms for owner/group, all for others |
| `9-John_Doe` | Sets hello permissions to -rwxr-x-wx |
| `10-mirror_permissions` | Sets hello permissions to match olleh's permissions |
| `11-directories_permissions` | Adds execute permission to all subdirectories |
| `12-directory_permissions` | Creates directory my_dir with permissions 751 |
| `13-change_group` | Changes group owner of hello to school |
| `14-change_owner_and_group` | Changes owner to vincent and group to staff for all files |
| `15-symbolic_link_permissions` | Changes owner and group of symbolic link _hello |
| `16-if_only` | Changes owner of hello to vincent only if owned by guillaume |
