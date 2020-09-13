# ansible-role-swarm-add-labels

### Required inventory:
```ansible
[managers]
10.0.10.1
10.0.10.2

[nodes]
10.0.10.1 hostname="manager_01" swarm_labels='["manager", "docker", "foo", "bar"]'
10.0.10.2 hostname="manager_02" swarm_labels='["manager", "docker", "foo", "bar"]'
10.0.110.1 hostname="worker_01" swarm_labels='["master", "docker", "foo", "bar"]'
10.0.110.2 hostname="worker_02" swarm_labels='["master", "docker", "foo", "bar"]'
10.0.110.3 hostname="worker_03" swarm_labels='["master", "docker", "foo", "bar"]'

[workers]
10.0.110.1
10.0.110.2
10.0.110.3
```
