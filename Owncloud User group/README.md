Creating user in own cloud using program.
Code:
sudo -u www-data php occ user:add \
 --display-name="Saurabh Wani" \
 --group="users" \
 --group="db-admins" \
--email=er.saurabhwani1@gmail.com Saurabh
Output:
 Enter password:
 Confirm password:
 The user "saurabh" was created successfully
 Display name set to "Saurabh Wani"
 Email address set to "er.saurabhwani1@gmail.com"
 User "saurabh" added to group "users"
User "saurabh" added to group "db-admins"
Deleting A User
sudo -u www-data php occ user:delete saurabh
Disable Users
sudo -u www-data php occ user:disable saurabh
Enable Users
sudo -u www-data php occ user:enable saurabh
