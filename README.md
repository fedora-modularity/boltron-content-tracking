# boltron-content-tracking
List of modules to be included in the F26 Boltron compose

| Module name         | Fixes | Stream | Ready for compose | Koji build | Image in registry |
| --------------------|-------|--------|-------------------|--------|-------------------|
|container-runtime    |built using bootstrap module | f26 | |[1186](https://koji.fedoraproject.org/koji/taginfo?tagID=1186) | |
|shared-userspace     | | f26 | |[1224](https://koji.fedoraproject.org/koji/taginfo?tagID=1224) | |
|mariadb              |should be fixed | f26 | |[893775](https://koji.fedoraproject.org/koji/buildinfo?buildID=893775) | |
|memcached            | | f26 | |[890176](https://koji.fedoraproject.org/koji/buildinfo?buildID=890176) |[memcached](docker.io/modularitycontainers/memcached) |
|haproxy              | | f26 | |[890180](https://koji.fedoraproject.org/koji/buildinfo?buildID=890180) |[haproxy](docker.io/modularitycontainers/haproxy) |
|perl                 | | f26 | |[888672](https://koji.fedoraproject.org/koji/buildinfo?buildID=888672) |[perl](docker.io/modularitycontainers/perl) |
|dhcp-server          | | f26 | |[881907](https://koji.fedoraproject.org/koji/buildinfo?buildID=881907) |[dhcp-server](docker.io/modularitycontainers/dhcp-server) |
|postgresql           | | f26 | |[884273](https://koji.fedoraproject.org/koji/buildinfo?buildID=884273) | |
|mongodb              | | f26 | |[890792](https://koji.fedoraproject.org/koji/buildinfo?buildID=890792) | |
|perl-libintl-perl    | | f26 | |[888373](https://koji.fedoraproject.org/koji/buildinfo?buildID=888373) | |
|perl-Unicode-EastAsianWidth | | f26 | |[888371](https://koji.fedoraproject.org/koji/buildinfo?buildID=888371) | |
|httpd                |using bootstrap | f26 | |[890082](https://koji.fedoraproject.org/koji/buildinfo?buildID=890082) | |
|nginx                |using bootstrap | f26 | |[868673](https://koji.fedoraproject.org/koji/buildinfo?buildID=868673) |[nginx](docker.io/modularitycontainers/nginx) |
|dhcp                 | | f26 | |[1163](https://koji.fedoraproject.org/koji/taginfo?tagID=1163) |[dhcp-client](docker.io/modularitycontainers/dhcp-client) |
|~~microdnf~~             | | f26 | |[885826](https://koji.fedoraproject.org/koji/buildinfo?buildID=885826) | |
|nodejs               | | f26 | |[19496188](https://koji.fedoraproject.org/koji/taskinfo?taskID=19496188) | |
|~~python2~~              |Cant do, some builed troubles  | f26 | | | |
|~~python3~~              |in BRT |  | | | |
|~~proftpd~~              | |  | | | |
|sssd (petr to confirm) | | | | | |
|varnish              |built using bootstrap module | f26 | |[19513341](https://koji.fedoraproject.org/koji/taskinfo?taskID=19513341) | |
|bind                 |wrong branch in distgit |  | | | |
|source-to-image      |using bootstrap | f26 | |[892445](https://koji.fedoraproject.org/koji/buildinfo?buildID=892445) | |
|php                  | | f26 | |[891394](https://koji.fedoraproject.org/koji/buildinfo?buildID=891394) | |
