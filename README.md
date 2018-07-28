#### SSH-Keys Automation
=============================


```bash
ansible-playbook -i ./hosts -l ssh_keys ./playbooks/ssh_keys.yml -v
```



if you are using ec2.py

$ export AWS_ACCESS_KEY_ID='YOUR_AWS_API_KEY'
$ export AWS_SECRET_ACCESS_KEY='YOUR_AWS_API_SECRET_KEY'

```bash
./ec2.py --list

ansible -i ec2.py -u schristman us-east-1d -m ping
```


