# monitorACL
QNAP fix for Active Directory permission issue between shared group domain users.  Uses inotify to create recurisve file monitor then sets specified acl with setfacl.  Run in autostart.sh.  Installed Entware (https://github.com/Entware/Entware/wiki/Install-on-QNAP-NAS) using http://bin.entware.net/other/Entware_1.00std.qpkg for compile tools, required, remember things don't persist on reboot so make sure everything is backed up before issuing a reboot.
Here's the list of enware packages I installed to get things working:

ar - 2.34-1

bc - 1.06.95-1

binutils - 2.34-1

busybox - 1.31.1-4

ca-bundle - 20200601-1

coreutils - 8.32-1

coreutils-install - 8.32-1

curl - 7.72.0-2

diffutils - 3.7-2

entware-opt - 227000-3

entware-release - 1.0-2

entware-upgrade - 1.0-1

findutils - 4.7.0-2

gawk - 5.1.0-1

gcc - 7.4.0-5

git - 2.27.0-1

git-http - 2.27.0-1

grep - 3.4-2

htop - 3.0.1-1

ldd - 2.27-11

libacl - 2.2.53-1

libattr - 2.4.48-2

libbfd - 2.34-1

libc - 2.27-11

libctf - 2.34-1

libcurl - 7.72.0-2

libgcc - 8.4.0-11

libiconv-full - 1.11.1-4

libintl-full - 0.19.8.1-2

libncurses - 6.2-1

libncursesw - 6.2-1

libopcodes - 2.34-1

libopenssl - 1.1.1g-1

libpcre - 8.44-2

libpthread - 2.27-11

libreadline - 8.0-1a

librt - 2.27-11

libssp - 8.4.0-11

libstdcpp - 8.4.0-11

locales - 2.27-9

make - 4.3-1

objdump - 2.34-1

opkg - 2020-05-07-f2166a89-1

patch - 2.7.6-6

sed - 4.8-3

terminfo - 6.2-1

vim - 8.2-2

wget - 1.20.3-4

zlib - 1.2.11-3

zoneinfo-asia - 2020a-1

zoneinfo-europe - 2020a-1
