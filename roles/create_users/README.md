#Create Users

Steps:

1. Read User list from a dictionary variable in YAML file
Format is as below

vars:
    users:
      chandan:
          name: chandan chowdhury
          groups: users,sudo
          authorized_key: Chandan_id_rsa.pub

2. Create User on target server with default password and add to groups 'users' and 'sudo'

3. Create the .ssh directory

4. Copy files/<Username>_id_rsa.pub to <User home>/.ssh/id_rsa.pub

5. Test
