# gitlab-user-management
Python scripts for GitLab user management.

## Requirement

* Python3
* python-gitlab(you can install with `pip install python-gitlab`)
* GitLab Private Access Token of "Admin" User

## setup

* clone and install python-gitlab

```
git clone git@github.com:msawady/gitlab-user-management.git
pip install python-gitlab
```

* write your GitLab url and your private access token on `python-gitlab.cfg`

```
cd gitlab-user-management
mv sample.python-gitlab.cfg python-gitlab.cfg
```

## add user

* Create csv file, sample is ./sample_add_user.csv
* Execute script

```
./add-user --csvfile filename.csv
```

## add user to group

* Create csv file, sample is ./sample_add_group.csv
* Execute script

```
./add-user --group --csvfile filename.csv
```

## TODO

* Enables to set access level when adding user on group.
