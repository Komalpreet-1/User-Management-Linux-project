# User-Management-Linux-project
In the current Linux environment, user and group management relies on a set of standard
utilities and manual configuration of system files:
 User and Group Management Commands:
o useradd: Adds a new user to the system.
o usermod: Modifies an existing user's details (e.g., changing passwords, groups).
o userdel: Deletes a user and optionally their home directory.
o groupadd: Creates a new group.
o groupdel: Deletes a group.
o passwd: Changes a user's password.
o chown: Changes file ownership.
o chmod: Changes file permissions.
 User Information Storage:
o /etc/passwd: Contains user account information, including username, user ID
(UID), group ID (GID), home directory, and shell.
o /etc/shadow: Stores user password hashes and password expiration information.
o /etc/group: Contains group information (group names, GIDs, and group members).
o /var/log/auth.log or /var/log/secure: Stores authentication logs, including
successful and failed login attempts.
o
While these utilities are powerful, they require knowledge of command-line syntax and manual
intervention for tasks such as bulk user creation, modification, and permission management.
The existing system lacks a cohesive, automated tool for managing users and groups, which can
be time-consuming and error-prone in large environments. 
