# Ansible-files-for-aggregating-ESXi-logs

This GitHub repository has Ansible files from a project I created in 2021, where I used Ansible to collect logs from my VMware ESXi home lab. For more information about the project, start with my first post: https://hightechdilettante.wordpress.com/2021/04/13/aggregating-esxi-logs-with-ansible/

I've uploaded two files to this repository. The first, named "playbook from the second blog post", includes a playbook I created that aggregates various logs on an ESXi server. Note that I designed the playbook to run on a remote device on the ESXi server, so that the remote device will collect logs. Also, keep in mind that I wrote it as a proof of concept. Optimizing it for log aggregation would require modify the code, and, really, Ansible is probably not the best option for that kind of functionality. 

The second file, named "Bash commands from the third blog post", is a script I wrote in Bash that aggregates logs like my Ansible playbook does. 
