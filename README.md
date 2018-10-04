### Ansible Code base to build out a cluster of media based raspberry pi devices.


There are five roles in total _nas_ , _osmc_ , _common_, _secure_, _media_

Notes: 

Dhcp must be mapped via mac-address on router (ips are hardcoded in these templates)

Run with `ansible-playbook -i production main.yml`

Jury is still out on ansible :)