# User Management in Central

Central is a cloud-based application for audio and video conferencing that records meetings and saves them to the cloud so users can have access to them anytime, anywhere. It is also used as a collaboration tool for teams and organizations.

This document serves as a comprehensive guide for administrators and user managers using Central. It aims to provide detailed instructions for adding users to Central, along with assigning them to specific user groups with defined permissions. By following this guide, you can efficiently manage user access within the Central application, ensuring streamlined operations and enhanced security.

## Adding a User to Central

This section describes how to add a new user to the Central using the console.

The following is an overview of the process for adding a user to the Central using the console.
1. Verifying prerequisites
2. Accessing the `User Management` tab
3. Adding a user
4. Deleting a user
      > You cannot recover a user's account once it is deleted.

### Verifying the Prerequisites 

Ensure the following prerequisites are met before adding a new user to the Central:

* Central Account: You must have an active account to log in to the Central portal.
* User Management Access: You must have any one of the following roles to access the `User Management` tab on the Central console:
    * Account administrator
    * Global administrator
    * User Management administrator

### Accessing the User Management Tab

This section describes how to access the `User Management` tab on the Central portal.

To access the `User Management` tab:

1. Log in to the [Central portal](https://central.portal.com).
2. Navigate to the `User Management` tab on the left pane.

### Adding a User

This section describes how to add a user to the Central portal.

To add a user:

1. On the `User Management` pane, click `Users`.
   
2. Select `Add User`.

   The page to add the basic details appears.
   
3. Enter the user's first and last name and a unique email address.

4. Click `Next`.

   The page to add the user to a user group appears.
   
5. Assign a user group to the user.
   You can either add the user to an existing user group or create a new user group.
   
   > For more information about creating a new user group, refer to [User Groups in Central](https://github.com/himanibirhade/Central-User-Management/blob/fc5b13fb0e6bffcad2b559c4806f60f0824f25e9/user_groups_in_central.md).
   
6. Click `Next`.

   The page to set permissions for the user appears.

7. Select the permissions you want to set for the user.

   > For more information about the different permissions that can be set for the user, refer to [Permissions in Central](https://github.com/himanibirhade/Central-User-Management/blob/9d057b6beae8fde838c25bb36bbdc5f43e24f129/permissions_in_central.md).

8. Click `Next`.

     The page to configure `Multi-factor authentication (MFA)` appears.
   
9. Configure the Multi-factor authentication (MFA) for the user.

   > For more information about MFA, refer to [Multi-Factor Authentication (MFA) in Central](https://github.com/himanibirhade/Central-User-Management/blob/46ba08da270b6598bc6058928af8acf0aacdd16b/mfa_in_central.md).
    
10. Click `Next`.

      The page to set up the first login password appears.
   
11. Set the first login password for the user. You can either set an auto-generated password or set a custom password.

      > Users must create a new password at the next sign-in.

12. Click `Next`.

      The page to review and add a user appears.
   
13. Verify the user details and then click `Add User`.
  
      The user has been added successfully.

### Deleting the User

This section describes how to delete a user from Central.

> **Warning**
  You cannot recover a user's account once it is deleted.

To delete a user from Central:

1. On the `User Management` pane, select `Users`.
2. Select `Delete User`.
3. Select the user you want to delete from Central.
4. Click `Delete User`.

The user has been deleted successfully.















