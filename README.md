# centos-dirty-cow-ansible
Ansible playbook to mitigate CVE-2016-5195 on CentOS with SystemTap.

Automating this mitigation recipe found on Red Hat Bugzilla:
https://bugzilla.redhat.com/show_bug.cgi?id=1384344#c13

## Disclaimer

I'm not a kernel security expert, nor a SystemTap expert. I've not verified effectiveness of this vulnerability mitigation recipe. I give no guarantees of any kind. This playbook may break your server and cause data loss for you.
