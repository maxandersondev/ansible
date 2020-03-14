# ansible
echo "# ansible" >> README.md

ansible-playbook -i ec2.py --private-key ~/.ssh/mca-aws-pair.pem tasks/nginx.yaml

