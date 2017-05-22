# boltron-content-tracking
List of modules to be included in the F26 Boltron compose

| Module name         | Ready for compose | Koji build | Image in registry |Notes |
| --------------------|-------------------|------------|-------------------|-------|
|container-runtime    |yes |[1186](https://koji.fedoraproject.org/koji/taginfo?tagID=1186) | |built using bootstrap module |
|shared-userspace     | |[1224](https://koji.fedoraproject.org/koji/taginfo?tagID=1224) | | |
|mariadb              | |[893775](https://koji.fedoraproject.org/koji/buildinfo?buildID=893775) | |should be fixed |
|memcached            |yes |[890176](https://koji.fedoraproject.org/koji/buildinfo?buildID=890176) |[memcached](docker.io/modularitycontainers/memcached) | |
|haproxy              |yes |[890180](https://koji.fedoraproject.org/koji/buildinfo?buildID=890180) |[haproxy](docker.io/modularitycontainers/haproxy) | |
|perl                 |yes |[888672](https://koji.fedoraproject.org/koji/buildinfo?buildID=888672) |[perl](docker.io/modularitycontainers/perl) | |
|~~dhcp-server~~          | |[881907](https://koji.fedoraproject.org/koji/buildinfo?buildID=881907) |[dhcp-server](docker.io/modularitycontainers/dhcp-server) ||
|postgresql           | |[884273](https://koji.fedoraproject.org/koji/buildinfo?buildID=884273) | | |
|mongodb              | |[890792](https://koji.fedoraproject.org/koji/buildinfo?buildID=890792) | | |
|perl-libintl-perl    |yes |[888373](https://koji.fedoraproject.org/koji/buildinfo?buildID=888373) | | |
|perl-Unicode-EastAsianWidth |yes |[888371](https://koji.fedoraproject.org/koji/buildinfo?buildID=888371) | | |
|httpd                |yes |[890082](https://koji.fedoraproject.org/koji/buildinfo?buildID=890082) | |using bootstrap |
|nginx                |yes |[868673](https://koji.fedoraproject.org/koji/buildinfo?buildID=868673) |[nginx](docker.io/modularitycontainers/nginx) |using bootstrap |
|dhcp                 | |[1163](https://koji.fedoraproject.org/koji/taginfo?tagID=1163) |[dhcp-client](docker.io/modularitycontainers/dhcp-client) |
|~~microdnf~~         | |[885826](https://koji.fedoraproject.org/koji/buildinfo?buildID=885826) | |
|nodejs               |  |[19496188](https://koji.fedoraproject.org/koji/taskinfo?taskID=19496188) | |
|~~python2~~          | | | |Cant do, some builed troubles  |
|~~python3~~          | | | |in BRT |
|~~proftpd~~          |  | | | |
|~~sssd~~ | | | | |
|varnish              |yes |[19513341](https://koji.fedoraproject.org/koji/taskinfo?taskID=19513341) | |built using bootstrap module |
|~~bind~~                 || | |wrong branch in distgit |
|~~source-to-image~~      | |[892445](https://koji.fedoraproject.org/koji/buildinfo?buildID=892445) | |using bootstrap |
|php                  | |[891394](https://koji.fedoraproject.org/koji/buildinfo?buildID=891394) | | |
