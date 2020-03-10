# gdal2-el8
```
dfn install dnf-plugins-core
dnf config-manager --set-enabled PowerTools
dnf install epel-release
dnf module enable ant maven javapackages-tools

git clone git@github.com:cmarmstrong/gdal2-el8.git
cd gdal-el8
dnf localinstall *.rpm
```
