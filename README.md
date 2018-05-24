# Ansible Role: elasticsearch [![Open in Cloud9](https://img.shields.io/badge/Open%20in-Cloud9-blue.svg?style=flat-square)](https://c9.io/auth/github?r=https%3A%2F%2Fc9.io%2Fopen%2F%3Fclone_url%3Dhttps%253A%252F%252Fgithub.com%252Fdenzuko-ansible-roles%252Felasticsearch.git) [![Analytics](https://ga-beacon.appspot.com/UA-110571074-1/denzuko/ansible-roles/elasticsearch?flat)](https://github.com/denzuko-ansible-roles/toelasticsearchr) [![CiCD](https://img.shields.io/travis/denzuko-ansible-roles/elasticsearch.svg?style=flat-square)](https://travis-ci.org/denzuko-ansible-roles/elasticsearch)

UA-110571074-1

Elastic Search Installer for CentOS

## Installation
$ ``` ansible-galaxy install denzuko.elasticsearch ```

## Requirements
* `ansible=>2.2`
* `Linux server`

## Files
This module Installs /etc/yum.d/elasticsearch.repo and [Elastic Search](https://www.elastic.co/products/elasticsearch)


## Usage

```yaml
- hosts: localhost
  roles:
     - role: comprescott.jre
     - role: denzuko.elasticsearch
```
