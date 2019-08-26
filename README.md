# ansible-cisco-backup-ssh
Ansible script Cisco devices for backup config via ssh

Download this YAML and add inventory hostname in /etc/ansible/hosts file with some variable

# example
[vcisco] <br>
192.168.31.[83:85] <br><br>

[vcisco:vars]<br>
ansible_network_os=ios <br>
ansible_ssh_user=your-cisco-ssh-user <br>
ansible_ssh_pass=your-cisco-ssh-passwd
