# Network Monitor Alarm

Systemd service to monitor network status and execute a command on failure of network.

## References

## Requirements
        Systemd

## Install
        $ sudo ./setup.sh

## Setup
1. Edit the configuration file, /etc/network-monitor-alarm.conf

2. Start the network-monitor-alarm Systemd timer

        $ sudo systemctl restart network-monitor-alarm.timer