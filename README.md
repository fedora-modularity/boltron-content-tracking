# boltron-content-tracking
List of modules to be included in the F26 Boltron compose

| Module name         | Stream | Ready for compose | Koji build | Image in registry |Notes |
| --------------------|--------|-------------------|------------|-------------------|-------|
|container-runtime    | f26 | |[1186](https://koji.fedoraproject.org/koji/taginfo?tagID=1186) | |built using bootstrap module |
|shared-userspace     |  f26 | |[1224](https://koji.fedoraproject.org/koji/taginfo?tagID=1224) | | |
|mariadb              | f26 | |[893775](https://koji.fedoraproject.org/koji/buildinfo?buildID=893775) | |should be fixed |
|memcached            |  f26 | |[890176](https://koji.fedoraproject.org/koji/buildinfo?buildID=890176) |[memcached](docker.io/modularitycontainers/memcached) | |
|haproxy              |  f26 | |[890180](https://koji.fedoraproject.org/koji/buildinfo?buildID=890180) |[haproxy](docker.io/modularitycontainers/haproxy) | |
|perl                 |  f26 | |[888672](https://koji.fedoraproject.org/koji/buildinfo?buildID=888672) |[perl](docker.io/modularitycontainers/perl) | |
|dhcp-server          |  f26 | |[881907](https://koji.fedoraproject.org/koji/buildinfo?buildID=881907) |[dhcp-server](docker.io/modularitycontainers/dhcp-server) | |
|postgresql           |  f26 | |[884273](https://koji.fedoraproject.org/koji/buildinfo?buildID=884273) | | |
|mongodb              |  f26 | |[890792](https://koji.fedoraproject.org/koji/buildinfo?buildID=890792) | | |
|perl-libintl-perl    |  f26 | |[888373](https://koji.fedoraproject.org/koji/buildinfo?buildID=888373) | | |
|perl-Unicode-EastAsianWidth |  f26 | |[888371](https://koji.fedoraproject.org/koji/buildinfo?buildID=888371) | | |
|httpd                | f26 | |[890082](https://koji.fedoraproject.org/koji/buildinfo?buildID=890082) | |using bootstrap |
|nginx                | f26 | |[868673](https://koji.fedoraproject.org/koji/buildinfo?buildID=868673) |[nginx](docker.io/modularitycontainers/nginx) |using bootstrap |
|dhcp                 | f26 | |[1163](https://koji.fedoraproject.org/koji/taginfo?tagID=1163) |[dhcp-client](docker.io/modularitycontainers/dhcp-client) |
|~~microdnf~~             | f26 | |[885826](https://koji.fedoraproject.org/koji/buildinfo?buildID=885826) | |
|nodejs               | f26 | |[19496188](https://koji.fedoraproject.org/koji/taskinfo?taskID=19496188) | |
|~~python2~~              | f26 | | | |Cant do, some builed troubles  |
|~~python3~~              |  | | | |in BRT |
|~~proftpd~~              | |  | | | |
|sssd (petr to confirm) | | | | | |
|varnish              | f26 | |[19513341](https://koji.fedoraproject.org/koji/taskinfo?taskID=19513341) | |built using bootstrap module |
|bind                 |  | | | |wrong branch in distgit |
|source-to-image      | f26 | |[892445](https://koji.fedoraproject.org/koji/buildinfo?buildID=892445) | |using bootstrap |
|php                  |  f26 | |[891394](https://koji.fedoraproject.org/koji/buildinfo?buildID=891394) | | |
