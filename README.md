# Fedora 26 Boltron - content tracking

List of modules to be included in the F26 Boltron compose


## Rationale

In order for a module to be included in Boltron release, the module, and all of
its build and runtime dependencies, need to be built in koji from the `f26`
branch. The difference between `yes` and `pending` states is that Factory 2.0
team verifies this requirement.

It is easily possible to break this requirement for all modules just by
building a module from `master` branch. Hence if such module would be
dependency of `shared-userspace` and `common-build-depedencies` modules, all
modules would be transitively dependent on it and thus would need to be rebuilt
against a properly built module.


**Ready for compose:**

* **yes** - the Factory 2.0 team confirmed it's ready
* pending - the Modularity team believes it's ready, waiting for Factory 2.0 confirmation
* no - excluded from the Fedora 26 Boltron release

| Module name         | Ready for compose | Koji build | Image in registry |Notes |
| --------------------|-------------------|------------|-------------------|-------|
|**container-runtime**    |**yes** |[1186](https://koji.fedoraproject.org/koji/taginfo?tagID=1186) | |built using bootstrap module |
|shared-userspace     |pending |[1407](https://koji.fedoraproject.org/koji/taginfo?tagID=1407) | |built using bootstrap module |
|mariadb              |pending |[893775](https://koji.fedoraproject.org/koji/buildinfo?buildID=893775) | |should be fixed |
|**memcached**            |**yes** |[890176](https://koji.fedoraproject.org/koji/buildinfo?buildID=890176) |[memcached](docker.io/modularitycontainers/memcached) | |
|**haproxy**              |**yes** |[890180](https://koji.fedoraproject.org/koji/buildinfo?buildID=890180) |[haproxy](docker.io/modularitycontainers/haproxy) | |
|**perl**                 |**yes** |[888672](https://koji.fedoraproject.org/koji/buildinfo?buildID=888672) |[perl](docker.io/modularitycontainers/perl) | |
|postgresql           |pending |[895240](https://koji.fedoraproject.org/koji/buildinfo?buildID=895240) | | |
|mongodb              |pending |[890792](https://koji.fedoraproject.org/koji/buildinfo?buildID=890792) | | |
|**perl-libintl-perl**    |**yes** |[888373](https://koji.fedoraproject.org/koji/buildinfo?buildID=888373) | | |
|**perl-Unicode-EastAsianWidth** |**yes** |[888371](https://koji.fedoraproject.org/koji/buildinfo?buildID=888371) | | |
|**httpd**                |**yes** |[890082](https://koji.fedoraproject.org/koji/buildinfo?buildID=890082) | |using bootstrap |
|**nginx**                |**yes** |[868673](https://koji.fedoraproject.org/koji/buildinfo?buildID=868673) |[nginx](docker.io/modularitycontainers/nginx) |using bootstrap |
|dhcp                 |pending |[1163](https://koji.fedoraproject.org/koji/taginfo?tagID=1163) |[dhcp-client](docker.io/modularitycontainers/dhcp-client) |
|**varnish**              |**yes** |[19513341](https://koji.fedoraproject.org/koji/taskinfo?taskID=19513341) | |built using bootstrap module |
|nodejs               |pending  |[19496188](https://koji.fedoraproject.org/koji/taskinfo?taskID=19496188) | |
|php                  |pending |[891394](https://koji.fedoraproject.org/koji/buildinfo?buildID=891394) | | |
|~~bind~~                 |no| | |wrong branch in distgit |
|source-to-image      |pending |[895876](https://koji.fedoraproject.org/koji/buildinfo?buildID=895876) | |using bootstrap |
|~~microdnf~~         |no |[885826](https://koji.fedoraproject.org/koji/buildinfo?buildID=885826) | |
|~~python2~~          |no | | |Cant do, some builed troubles  |
|~~python3~~          |no | | |in BRT |
|~~proftpd~~          |no  | | | |
| sssd | pending |[896001](https://koji.fedoraproject.org/koji/buildinfo?buildID=896001) | | using bootstrap |
|~~dhcp-server~~          |no |[881907](https://koji.fedoraproject.org/koji/buildinfo?buildID=881907) |[dhcp-server](docker.io/modularitycontainers/dhcp-server) ||
| postfix | pending | [896564](https://koji.fedoraproject.org/koji/buildinfo?buildID=896564) |[postfix](docker.io/modularitycontainers/postfix)|
