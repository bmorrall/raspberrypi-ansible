# RaspberryPi Ansible

My Personal Configuration for setting up a Raspberry Pi

## System Setup (OS X)

```
cp hosts.example hosts
ansible-playbook -i hosts smarthome.yml --ask-pass
```

## Notes

Smarthome service can be manually enabled and started with:

```
sudo systemctl enable smarthome.service
sudo systemctl start smarthome.service
```

Check the status with:

```
sudo systemctl status smarthome.service
```
