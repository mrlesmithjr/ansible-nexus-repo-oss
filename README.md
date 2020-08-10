# ansible-nexus-repo-oss

Ansible role to install/configure [Sonatype Nexus Repo OSS](https://www.sonatype.com/nexus-repository-oss)

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-nexus-repo-oss/workflows/Molecule%20Test/badge.svg)

### Travis CI

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-nexus-repo-oss.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-nexus-repo-oss)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

## Setting Up Clients

### CentOS

```bash
[base]
name=CentOS-$releasever - Base
baseurl=http://192.168.250.11:8081/repository/centos/$releasever/os/$basearch/

[updates]
name=CentOS-$releasever - Updates
baseurl=http://192.168.250.11:8081/repository/centos/$releasever/updates/$basearch/

[extras]
name=CentOS-$releasever - Extras
baseurl=http://192.168.250.11:8081/repository/centos/$releasever/extras/$basearch/
```

### Ubuntu

```bash
deb http://192.168.250.11:8081/repository/bionic/ bionic main restricted
deb http://192.168.250.11:8081/repository/bionic/ bionic-updates main restricted
deb http://192.168.250.11:8081/repository/bionic/ bionic universe
deb http://192.168.250.11:8081/repository/bionic/ bionic-updates universe
deb http://192.168.250.11:8081/repository/bionic/ bionic multiverse
deb http://192.168.250.11:8081/repository/bionic/ bionic-updates multiverse
deb http://192.168.250.11:8081/repository/bionic/ bionic-backports main restricted universe multiverse
```

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
