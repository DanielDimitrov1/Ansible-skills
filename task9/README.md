Create the users in the file users_list.yml file provided. Do this in a playbook called users.yml located at /home/tom/ansible. The passwords for these users should be set using the stat.yml file from the previous task. When running the playbook. stat.yml file should be unlocked with secret.txt file from previous task.
All users with the job of 'developer' should be created on the dev hosts, add them to the group devops their password should be set using pawd_dev variable. Likewise create users with the job of
'manager' on the proxy host and add the users to the group 'manager', their password should be set using the pawd_mgr variable.

users:

  - username: bill

    job: developer

  - username: chris

    job: manager

  - username: dave

    job: test

  - username: ethan

    job: developer
