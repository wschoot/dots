# dots
Start with preparing your system by installing dependencies -- needs sudo

```
ansible-playbook --connection=local -i localhost, setupdots.yml
```

Proceed with copying the required dotfiles, no sudo required.

```
ansible-playbook --connection=local -i localhost, copydots.yml
```
