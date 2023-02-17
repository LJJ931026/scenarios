# Modify File Permissions

This challenge is about modifying the file permissions.

Before we are challenged to learn about modifying file permissions, let's first understand what we need to know about file permissions

## File Permissions

Linux/Unix file permissions are classified into three levels: Owner, Group, and Other Users.

![challenge-file-properties-3-1](./assets/challenge-file-properties-3-1.png)

After creating a file with `touch` command, the Owner and Group have read and write permission, but the Other Users only has read permission.

![challenge-file-properties-3-2](./assets/challenge-file-properties-3-2.png)

![challenge-file-properties-3-3](./assets/challenge-file-properties-3-3.png)

## Example

![challenge-file-properties-3-4](./assets/challenge-file-properties-3-4.png)


## Requirements

- Create a file named `setup.sh` in the `~` directory with `touch` command.
- Add executable permissions to Other Users of the `setup.sh` script file.
