danpalmer-ansible
-----------------

To run the main Ansible playbook:

```
$ ./run site
```

To add a new service:

1. Add its domain and Let's Encrypt compatible nginx configuration.
2. Run playbook to deploy certificates.
3. Add necessary databases manually.
4. Add configuration for the actual service, nginx proxying, etc.
