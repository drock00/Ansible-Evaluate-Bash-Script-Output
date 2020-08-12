
# Ansible-Lecter-Script-Result-Control-Status

### Ansible - Scripts that Depend on Particular Output for Task Success

Here a simple bash script was created that, when run, accepts a single argument. That argument is echoed as output to the terminal. Sometimes success depends on what is being output to the terminal from the script. In the yesno program, if the script outputs 'yes' then the task succeeds. However if it outputs anything other than yes, then the task will fail. Here the argument is hardcoded to 'yes', but it can be changed to anything else on run. 

# Run
```sh
$ ansible-playbook yesnostatus.yml 
```

### Tech and Running the file

Bada Bin Bada Bash Bada Boom. Throw up a couple virtual servers and edit the inventory here to match your settings. Run the file as above. 