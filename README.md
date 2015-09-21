# Phansible Role: Apache

[![Build Status](https://travis-ci.org/debo/phansible-role-apache.svg?branch=master)](https://travis-ci.org/debo/phansible-role-apache)

An Ansible Role that installs [Apache](http://httpd.apache.org/) on CentOS and Ubuntu specifically created with [Phansible](http://phansible.com/) in mind.

## Requirements

// TODO

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
apache:
    docroot: "/var/www/html"
    servername: "phansible.dev"
```

Add `servername` and `documentroot` set of properties to the default virtualhost.

## Dependencies

// TODO

## Example Playbook

// TODO

## License

The MIT License

Copyright (c) 2015 [Marco "Debo" De Bortoli](http://debo.io/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Author Information

This role was created in 2015 by [Marco "Debo" De Bortoli](http://debo.io/), credits go also to [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/) and source of inspiration.
