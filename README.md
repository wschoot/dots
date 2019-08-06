# dots
Start with preparing your system by installing dependencies -- needs sudo

```
ansible-playbook --connection=local -i localhost, setupdots.yml
```

Proceed with copying the required dotfiles, no sudo required.

```
ansible-playbook --connection=local -i localhost, copydots.yml
```

Fill in the variables for localhost, as shown in host_vars/localhost.yml
To prevent commiting changes to this file:

```
git update-index --assume-unchanged
```
