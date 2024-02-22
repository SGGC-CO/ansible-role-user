# ansible-role-user

Add a user to the server.

## Requirements

ssh key should be added to the server.

## Variables

1. playbook.yml

```yaml
user_name: "username of the user"
user_password: "password of the user"
```

2. inventory.ini

```yaml
user: "username of the server"
ssh_private_key_file: "path to private key file"
```

## Dependencies

none

## Example Playbook

`tests/test.yml`

`cd tests` and run the playbook with the following command:

```yaml
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory.ini test.yml
```

## License

BSD

## Author Information

telegram: [@Qteam1](https://t.me/Qteam1)
