# ansible-playbook - set-authorized-key

Very basic ansible playbook that sets root's authorized key

## Instructions

1. Install ansible-playbook
2. Create a hosts file with your target host
3. Run the playbook in the project directory, providing the root password:

```
ansible-playbook -i hosts -u root --ask-pass main.yml
```

