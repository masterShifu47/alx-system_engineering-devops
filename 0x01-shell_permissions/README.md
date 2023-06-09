# Shell Permissions Scripts

This project contains a set of shell scripts that perform various actions related to shell permissions. Each script is designed to accomplish a specific task, as outlined below. 

## Script Descriptions

1. **switch_user.sh**: This script switches the current user to the user "betty" using the `su` command.

2. **get_username.sh**: This script prints the effective username of the current user using the `whoami` command.

3. **get_groups.sh**: This script prints all the groups the current user is part of using the `groups` command.

4. **change_owner.sh**: This script changes the owner of the file "hello" to the user "betty" using the `chown` command.

5. **create_empty_file.sh**: This script creates an empty file called "hello" using the `touch` command.

6. **add_execute_permission.sh**: This script adds execute permission to the owner of the file "hello" using the `chmod` command.

7. **add_multiple_permissions.sh**: This script adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello" using the `chmod` command.

8. **add_all_permissions.sh**: This script adds execution permission to the owner, the group owner, and the other users, to the file "hello" using the `chmod` command.

9. **set_specific_permissions.sh**: This script sets the permission to the file "hello" as follows:
   - Owner: no permission at all
   - Group: no permission at all
   - Other users: all the permissions
   It uses the `chmod` command with the numeric mode 007.

10. **set_mode_from_another_file.sh**: This script sets the mode of the file "hello" the same as the mode of the file "olleh". It uses the `stat` command to retrieve the file mode and the `chmod` command to modify the file permissions.

## License
This project is licensed under the ALX SE License. For more information, please see the [LICENSE](LICENSE) file.

Feel free to modify or extend these scripts to suit your specific needs.
