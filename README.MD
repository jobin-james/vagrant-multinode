You can use this vagrant file to create Multimple varrant nodes at once.
Please update the required node number, name, RAM, etc in mainfest.yml.
---
  instances: 2
  provider: virtualbox
  name_prefix: server0
  name_suffix: .test.local
  ip_prefix: 192.168.1.33
  disk_size: 20G
  memory: 2048
  cpus: 2
  box: ubuntu/trusty64
