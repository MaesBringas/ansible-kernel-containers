# ansible-kernel-containers
Ansible playbook to check kernel parameters to production systems that uses containers.

Tested in CentOS 7 for kernel 4.9.
Applied GrSecurity patches, checks kernel configurations to content
applications as Docker or Linux Containers (LXC).

# How to use:

``` bash
ansible-playbook host -i kernel.yml --extra-vars "kernel_version='4.9' "
```

# References
- https://wiki.centos.org/es/HowTos/Custom_Kernel
- https://forum.level1techs.com/t/how-to-configuring-and-installing-a-grsecurity-kernel/89954
