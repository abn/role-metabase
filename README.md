# Ansible Role: Metabase
This role allows for the installation of metabase server on a host via [community provided rpm package](https://github.com/abn/metabase-rpm).

### Dependencies
* [Copr Repository Role](https://github.com/abn/role-copr-repository)

### Variables
* `metabase_version`: RPM package version of metabase to install
* `metabase_variables`: List of k/v pairs to add into sysconfig file
