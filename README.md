#R1Soft cPanel Paper Lantern
============================


To register the R1Soft module in paper lantern, you need to do a few things.

First thing is to move the `r1redirect.php` file to the paper_lantern folder:

```
cp ~/r1soft-cpanel-plugin-1.1/r1redirect.php /usr/local/cpanel/base/frontend/paper_lantern/
```

After this we need to register the plugin in Paper Lantern as well.

First download this repository:

```
cd ~ && wget https://github.com/lucasRolff/r1soft-cpanel-paper_lantern/archive/master.zip
```

Once downloaded, you can install it right away.

```
unzip ~/master.zip && rm ~/master.zip
/usr/local/cpanel/scripts/install_plugin ~/r1soft-cpanel-paper_lantern-master
```

After this the installation should be done, and the icon should show up in Paper Lantern
