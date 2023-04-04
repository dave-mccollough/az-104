# Manage Azure AD objects

## Create users and groups
- Azure AD manages both users and applications
    - Create new users
    - Invite users from outside your tenant
- You can sync with on-prem active directory and sync users (AD Connect)
- Groups are a collection of users who have been given specific permissions to resources in the Microsoft cloud
- Groups are an organizational structure
- Azure AD roles can be assigend to a group
- Groups can be dynamic (Membership type:  Dynamic User)
    - Users can be automatically assigned to a group based on department, location, country, etc
        - Rules are configured to create a dynamic membership rule
            - If a new user is added to a department, they will be automatically added to the group

## Manage licenses in Azure AD
- Licenses have to be assigned to users
- Users may have to have a usage location specified in order for licenses to be assigned to them
    - Usage location is defined in the user properties
- Only assign licences to users based on their needs/requirements

## Create administrative units
- An administrative unit can contain users, groups, or devices.
- Administrative units restrict permissions in a role to any portion of your organization that you define.
- Once adminstrative unit is created, you can add users, groups, or devices to that administrative unit

- Administrative units restrict permissions in a role to any portion of your organization that you define.

## Manage device settings and device identity
- Devices are physical devices used by users who access that access organization resources authenticated by Azure
- Tracks managed and unmanaged devices
    - Managed devices
        - Define standards such as encryption, password requirements, anti-virus
        - Only devices that meet established standards can access an application
        - Used with conditional access

## Perform bulk updates
- Bulk create feature lets you upload users with a .csv file
- You can download a .csv template

## Manage guest accounts
- Users not in your domain are guest users
- Guest users are external users who are granted access to your organization's resources
    - Typically partners, vendors, or contractors
- Click **Invite user** radio button to invite guest users 
- Guest users are assigned permissions just like interal users
- Invitation can include personal message

## Configure self-service password reset
- Self service password reset allows users to reset their passwords without contacting an administrator or permissioned user to reset for them
- Users of free tier Azure AD do not have access to self-service password reset
- Microsoft enforces MFA and allows self-service password reset for administrative users


