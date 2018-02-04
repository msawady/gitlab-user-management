# gitlab-user-management
Python scripts for GitLab user management.

## Requirement

* Python3
* python-gitlab(you can install with `pip install python-gitlab`)
* GitLab Private Access Token of "Admin" User

## add user

* Create csv file, sample is ./sample_add_user.csv
* Execute script

```
./add-user --token {yourToken} --csvfile filename.csv
```

## add user to group

* Create csv file, sample is ./sample_add_group.csv
* Execute script

```
./add-user --group --token {yourToken} --csvfile filename.csv
```

## TODO

* Enables to set access level when adding user on group.
