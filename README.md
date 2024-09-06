# ansible-cisco-telemetry
This is a demo intended to be run on top of a student lab from an Ansible Network Workshop. (see: https://github.com/ansible/workshops)

It demonstrates Event-Driven Ansible self-healing from BGP configuration problems with the following additional topics:
- Using the validated network.telemetry collection to install a Telegraf/Kafka stack in Docker containers (see: https://github.com/redhat-cop/network.telemetry)
- Installing and browsing Cisco YANG Suite to find additional xpaths to monitor (see: https://developer.cisco.com/docs/yangsuite/)