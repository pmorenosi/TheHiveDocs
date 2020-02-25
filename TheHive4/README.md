# TheHive 4 : Installation, administration and user guides




## Notes

- The documentation is illustrated using Ubuntu 18.04 LTS as base system. 

## Hardware Pre-requisites

## Installation and configuration Guides


- [Prepare your environment](Installation/Prepare.md)
- [Installation](Installation/Installation.md)
	- Using DEB package
	- Using RPM package
	- Using binaries
- [Base configuration](Installation/Base_configuration.md)


## Administration Guides

- [Authentication](Administration/Authentication.md)
	- LDAP/AD
	- OAuth2/OpenID Connect
	- Single Sign-On TheHive with X.509 Certificates
- [Connectors](Administration/Connectors.md) 
	- Connect TheHive to one or more Cortex instances
	- Connect TheHive to one or more MISP instances
- [HTTPS](Administration/HTTPS.md)
	- HTTPS using a reverse proxy
	- HTTPS without reverse proxy
	- Strenghten security
- [Migration](Administration/Migration.md)
	- Migrate your data from TheHive 3.4.x to TheHive 4.0-RC1
- [Backup & Restore](Administration/Backup_Restore.md)
	- Backup and Restore Cassandra database
	- Backup and Restore Hadoop distributed FileSystem
- [Clustering TheHive](Administration/Clustering.md)
	- Cassandra database advanced configuration
	- Using Hadoop filesystem
	- Insert TheHive in a cluster

## User guides

### Quick start

By default, TheHive comes with a default local organisation named `thehive.local` and a default Admin user `admin@thehive.local`. The associated default password is `secret`.  You are strongly invited to update the password as soon as possible.

The organisation `thehive.local` is the Organisation that contains global administration users and are in charge of managing:

- Organisations and users,
- TheHive report templates, 
- Custom Fields

### Administration space

- [Manage Organisations & Users](User/manage_orgs_users.md)
	- Introducing Roles and Shares
	- Create/Update/Delete Organisations
	- Create/Update/Delete Users
	- Link Organisations
- [Add report templates](User/Report_templates.md)
- [CustomFields](User/CustomFields.md)


## REST API


## License
TheHive is an open source and free software released under the [AGPL](https://github.com/TheHive-Project/TheHive/blob/master/LICENSE) (Affero General Public License). We, TheHive Project, are committed to ensure that TheHive will remain a free and open source project on the long-run.

## Updates
Information, news and updates are regularly posted on [TheHive Project Twitter account](https://twitter.com/thehive_project) and on [the blog](https://blog.thehive-project.org/).

## Contributing
We welcome your contributions. Please feel free to fork the code, play with it, make some patches and send us pull requests using [issues](https://github.com/TheHive-Project/TheHive/issues).

We do have a [Code of conduct](code_of_conduct.md). Make sure to check it out before contributing.

## Support
Please [open an issue on GitHub](https://github.com/TheHive-Project/TheHive/issues) if you'd like to report a bug or request a feature. We are also available on [Gitter](https://gitter.im/TheHive-Project/TheHive) to help you out.

If you need to contact the Project's team, send an email to <support@thehive-project.org>.

**Important Note**:

- If you have problems with [TheHive4py](https://github.com/TheHive-Project/TheHive4py), please [open an issue on its dedicated repository](https://github.com/TheHive-Project/TheHive4py/issues/new).
- If you encounter an issue with Cortex or would like to request a Cortex-related feature, please [open an issue on its dedicated GitHub repository](https://github.com/TheHive-Project/Cortex/issues/new).
- If you have troubles with a Cortex analyzer or would like to request a new one or an improvement to an existing analyzer, please open an issue on the [analyzers' dedicated GitHub repository](https://github.com/TheHive-Project/cortex-analyzers/issues/new).

## Community Discussions
We have set up a Google forum at <https://groups.google.com/a/thehive-project.org/d/forum/users>. To request access, you need a Google account. You may create one [using a Gmail address](https://accounts.google.com/SignUp?hl=en) or [without it](https://accounts.google.com/SignUpWithoutGmail?hl=en).

## Website
<https://thehive-project.org/>
