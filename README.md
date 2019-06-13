# kafka
This role can be used to install and cluster multiple Kafka nodes, this uses all hosts defined for the "kafka-nodes" group in the inventory file by default.


This role will install only install kafka. There is a seperate role for zookeeper installation and is needed for the kafka to work.
Zookeeper role can be downloaded from the galaxy link,
ansible-galaxy install ajtalla.zookeeper_install

Requirements

Platform: RHEL / CentOS 7

Java: Java 8
