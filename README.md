# squid
Fork from upstream with a patch to disable host header forgery checks.

Original source, `c7` branch:
```
git remote add centos https://git.centos.org/rpms/squid.git
```


## Build

```
cp SPECS/squid.spec SOURCES/squid.spec
cd SOURCES
makerpms squid.spec
```
