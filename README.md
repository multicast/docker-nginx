# nginx

![Pulls](https://img.shields.io/docker/pulls/mkovac/nginx.svg)
![Stars](https://img.shields.io/docker/stars/mkovac/nginx.svg)

The [NGINX](https://packages.debian.org/buster/nginx) on the [Debian](https://debian.org/) [Buster](https://wiki.debian.org/DebianBuster)
[container image](https://hub.docker.com/r/mkovac/nginx/).

This image is built daily and in case of any security update, the list of
packages is updated, commited and this triggers update of docker-hub image
and all dependant images.

This image is built daily and in case of any security update, the list of
packages is updated, commited and this triggers update of docker-hub image
and all dependant images.

## Quick Usage

Run prebuilt and explore:

    $ docker run --rm -ti mkovac/nginx bash

Typically you want to provide bind config files and mount them:

    $ docker run --rm -d -v /volumes/nginx:/etc/nginx:Z mkovac/nginx

# Packages

    Desired=Unknown/Install/Remove/Purge/Hold
    | Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
    |/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
    ||/ Name                                  Version                     Architecture Description
    +++-=====================================-===========================-============-===============================================================================
    ii  adduser                               3.118                       all          add and remove users and groups
    ii  apt                                   1.8.2.3                     amd64        commandline package manager
    ii  apt-utils                             1.8.2.3                     amd64        package management related utility programs
    ii  base-files                            10.3+deb10u13               amd64        Debian base system miscellaneous files
    ii  base-passwd                           3.5.46                      amd64        Debian base system master password and group files
    ii  bash                                  5.0-4                       amd64        GNU Bourne Again SHell
    ii  bsdutils                              1:2.33.1-0.1+deb10u1        amd64        basic utilities from 4.4BSD-Lite
    ii  ca-certificates                       20200601~deb10u2            all          Common CA certificates
    ii  coreutils                             8.30-3                      amd64        GNU core utilities
    ii  cron                                  3.0pl1-134+deb10u1          amd64        process scheduling daemon
    ii  curl                                  7.64.0-4+deb10u9            amd64        command line tool for transferring data with URL syntax
    ii  dash                                  0.5.10.2-5                  amd64        POSIX-compliant shell
    ii  debconf                               1.5.71+deb10u1              all          Debian configuration management system
    ii  debian-archive-keyring                2019.1+deb10u2              all          GnuPG archive keys of the Debian archive
    ii  debianutils                           4.8.6.1                     amd64        Miscellaneous utilities specific to Debian
    ii  di                                    4.47-1                      amd64        advanced df like disk information utility
    ii  diffutils                             1:3.7-3                     amd64        File comparison utilities
    ii  dpkg                                  1.19.8                      amd64        Debian package management system
    ii  dumb-init                             1.2.2-1.1                   amd64        wrapper script which proxies signals to a child
    ii  e2fsprogs                             1.44.5-1+deb10u3            amd64        ext2/ext3/ext4 file system utilities
    ii  etckeeper                             1.18.10-1                   all          store /etc in git, mercurial, bzr or darcs
    ii  fdisk                                 2.33.1-0.1+deb10u1          amd64        collection of partitioning utilities
    ii  findutils                             4.6.0+git+20190209-2        amd64        utilities for finding files--find, xargs
    ii  fontconfig-config                     2.13.1-2                    all          generic font configuration library - configuration
    ii  fonts-dejavu-core                     2.37-1                      all          Vera font family derivate with additional characters
    ii  gcc-8-base:amd64                      8.3.0-6                     amd64        GCC, the GNU Compiler Collection (base package)
    ii  git                                   1:2.20.1-2+deb10u9          amd64        fast, scalable, distributed revision control system
    ii  git-man                               1:2.20.1-2+deb10u9          all          fast, scalable, distributed revision control system (manual pages)
    ii  gpgv                                  2.2.12-1+deb10u2            amd64        GNU privacy guard - signature verification tool
    ii  grep                                  3.3-1                       amd64        GNU grep, egrep and fgrep
    ii  gzip                                  1.9-3+deb10u1               amd64        GNU compression utilities
    ii  hostname                              3.21                        amd64        utility to set/show the host name or domain name
    ii  init-system-helpers                   1.56+nmu1                   all          helper tools for all init systems
    ii  iproute2                              4.20.0-2+deb10u1            amd64        networking and traffic control tools
    ii  iputils-ping                          3:20180629-2+deb10u2        amd64        Tools to test the reachability of network hosts
    ii  joe                                   4.6-1+b1                    amd64        user friendly full screen text editor
    ii  less                                  487-0.1+deb10u1             amd64        pager program similar to more
    ii  libacl1:amd64                         2.2.53-4                    amd64        access control list - shared library
    ii  libapt-inst2.0:amd64                  1.8.2.3                     amd64        deb package format runtime library
    ii  libapt-pkg5.0:amd64                   1.8.2.3                     amd64        package management runtime library
    ii  libattr1:amd64                        1:2.4.48-4                  amd64        extended attribute handling - shared library
    ii  libaudit-common                       1:2.8.4-3                   all          Dynamic library for security auditing - common files
    ii  libaudit1:amd64                       1:2.8.4-3                   amd64        Dynamic library for security auditing
    ii  libblkid1:amd64                       2.33.1-0.1+deb10u1          amd64        block device ID library
    ii  libbsd0:amd64                         0.9.1-2+deb10u1             amd64        utility functions from BSD systems - shared library
    ii  libbz2-1.0:amd64                      1.0.6-9.2~deb10u2           amd64        high-quality block-sorting file compressor library - runtime
    ii  libc-bin                              2.28-10+deb10u4             amd64        GNU C Library: Binaries
    ii  libc-l10n                             2.28-10+deb10u4             all          GNU C Library: localization files
    ii  libc6:amd64                           2.28-10+deb10u4             amd64        GNU C Library: Shared libraries
    ii  libcap-ng0:amd64                      0.7.9-2                     amd64        An alternate POSIX capabilities library
    ii  libcap2:amd64                         1:2.25-2                    amd64        POSIX 1003.1e capabilities (library)
    ii  libcap2-bin                           1:2.25-2                    amd64        POSIX 1003.1e capabilities (utilities)
    ii  libcom-err2:amd64                     1.44.5-1+deb10u3            amd64        common error description library
    ii  libcurl3-gnutls:amd64                 7.64.0-4+deb10u9            amd64        easy-to-use client-side URL transfer library (GnuTLS flavour)
    ii  libcurl4:amd64                        7.64.0-4+deb10u9            amd64        easy-to-use client-side URL transfer library (OpenSSL flavour)
    ii  libdb5.3:amd64                        5.3.28+dfsg1-0.5            amd64        Berkeley v5.3 Database Libraries [runtime]
    ii  libdebconfclient0:amd64               0.249                       amd64        Debian Configuration Management System (C-implementation library)
    ii  libelf1:amd64                         0.176-1.1+deb10u1           amd64        library to read and write ELF files
    ii  liberror-perl                         0.17027-2                   all          Perl module for error/exception handling in an OO-ish way
    ii  libexpat1:amd64                       2.2.6-2+deb10u7             amd64        XML parsing C library - runtime library
    ii  libext2fs2:amd64                      1.44.5-1+deb10u3            amd64        ext2/ext3/ext4 file system libraries
    ii  libfdisk1:amd64                       2.33.1-0.1+deb10u1          amd64        fdisk partitioning library
    ii  libffi6:amd64                         3.2.1-9                     amd64        Foreign Function Interface library runtime
    ii  libfontconfig1:amd64                  2.13.1-2                    amd64        generic font configuration library - runtime
    ii  libfreetype6:amd64                    2.9.1-3+deb10u3             amd64        FreeType 2 font engine, shared library files
    ii  libgcc1:amd64                         1:8.3.0-6                   amd64        GCC support library
    ii  libgcrypt20:amd64                     1.8.4-5+deb10u1             amd64        LGPL Crypto library - runtime library
    ii  libgd3:amd64                          2.2.5-5.2+deb10u1           amd64        GD Graphics Library
    ii  libgdbm-compat4:amd64                 1.18.1-4                    amd64        GNU dbm database routines (legacy support runtime version) 
    ii  libgdbm6:amd64                        1.18.1-4                    amd64        GNU dbm database routines (runtime version) 
    ii  libgeoip1:amd64                       1.6.12-1                    amd64        non-DNS IP-to-country resolver library
    ii  libgmp10:amd64                        2:6.1.2+dfsg-4+deb10u1      amd64        Multiprecision arithmetic library
    ii  libgnutls30:amd64                     3.6.7-4+deb10u12            amd64        GNU TLS library - main runtime library
    ii  libgpg-error0:amd64                   1.35-1                      amd64        GnuPG development runtime library
    ii  libgssapi-krb5-2:amd64                1.17-3+deb10u6              amd64        MIT Kerberos runtime libraries - krb5 GSS-API Mechanism
    ii  libhiredis0.14:amd64                  0.14.0-3                    amd64        minimalistic C client library for Redis
    ii  libhogweed4:amd64                     3.4.1-1+deb10u1             amd64        low level cryptographic library (public-key cryptos)
    ii  libicu63:amd64                        63.1-6+deb10u3              amd64        International Components for Unicode
    ii  libidn2-0:amd64                       2.0.5-1+deb10u1             amd64        Internationalized domain names (IDNA2008/TR46) library
    ii  libjbig0:amd64                        2.1-3.1+b2                  amd64        JBIGkit libraries
    ii  libjpeg62-turbo:amd64                 1:1.5.2-2+deb10u1           amd64        libjpeg-turbo JPEG runtime library
    ii  libk5crypto3:amd64                    1.17-3+deb10u6              amd64        MIT Kerberos runtime libraries - Crypto Library
    ii  libkeyutils1:amd64                    1.6-6                       amd64        Linux Key Management Utilities (library)
    ii  libkrb5-3:amd64                       1.17-3+deb10u6              amd64        MIT Kerberos runtime libraries
    ii  libkrb5support0:amd64                 1.17-3+deb10u6              amd64        MIT Kerberos runtime libraries - Support library
    ii  libldap-2.4-2:amd64                   2.4.47+dfsg-3+deb10u7       amd64        OpenLDAP libraries
    ii  libldap-common                        2.4.47+dfsg-3+deb10u7       all          OpenLDAP common files for libraries
    ii  libluajit-5.1-2:amd64                 2.1.0~beta3+dfsg-5.1        amd64        Just in time compiler for Lua - library version
    ii  libluajit-5.1-common                  2.1.0~beta3+dfsg-5.1        all          Just in time compiler for Lua - common files
    ii  liblz4-1:amd64                        1.8.3-1+deb10u1             amd64        Fast LZ compression algorithm library - runtime
    ii  liblzma5:amd64                        5.2.4-1+deb10u1             amd64        XZ-format compression library
    ii  libmnl0:amd64                         1.0.4-2                     amd64        minimalistic Netlink communication library
    ii  libmount1:amd64                       2.33.1-0.1+deb10u1          amd64        device mounting library
    ii  libncurses6:amd64                     6.1+20181013-2+deb10u5      amd64        shared libraries for terminal handling
    ii  libncursesw6:amd64                    6.1+20181013-2+deb10u5      amd64        shared libraries for terminal handling (wide character support)
    ii  libnettle6:amd64                      3.4.1-1+deb10u1             amd64        low level cryptographic library (symmetric and one-way cryptos)
    ii  libnewt0.52:amd64                     0.52.20-8                   amd64        Not Erik's Windowing Toolkit - text mode windowing with slang
    ii  libnghttp2-14:amd64                   1.36.0-2+deb10u3            amd64        library implementing HTTP/2 protocol (shared library)
    ii  libnginx-mod-http-auth-pam            1.14.2-2+deb10u5            amd64        PAM authentication module for Nginx
    ii  libnginx-mod-http-cache-purge         1.14.2-2+deb10u5            amd64        Purge content from Nginx caches
    ii  libnginx-mod-http-dav-ext             1.14.2-2+deb10u5            amd64        WebDAV missing commands support for Nginx
    ii  libnginx-mod-http-echo                1.14.2-2+deb10u5            amd64        Bring echo and more shell style goodies to Nginx
    ii  libnginx-mod-http-fancyindex          1.14.2-2+deb10u5            amd64        Fancy indexes module for the Nginx
    ii  libnginx-mod-http-geoip               1.14.2-2+deb10u5            amd64        GeoIP HTTP module for Nginx
    ii  libnginx-mod-http-headers-more-filter 1.14.2-2+deb10u5            amd64        Set and clear input and output headers for Nginx
    ii  libnginx-mod-http-image-filter        1.14.2-2+deb10u5            amd64        HTTP image filter module for Nginx
    ii  libnginx-mod-http-lua                 1.14.2-2+deb10u5            amd64        Lua module for Nginx
    ii  libnginx-mod-http-ndk                 1.14.2-2+deb10u5            amd64        Nginx Development Kit module
    ii  libnginx-mod-http-perl                1.14.2-2+deb10u5            amd64        Perl module for Nginx
    ii  libnginx-mod-http-subs-filter         1.14.2-2+deb10u5            amd64        Substitution filter module for Nginx
    ii  libnginx-mod-http-uploadprogress      1.14.2-2+deb10u5            amd64        Upload progress system for Nginx
    ii  libnginx-mod-http-upstream-fair       1.14.2-2+deb10u5            amd64        Nginx Upstream Fair Proxy Load Balancer
    ii  libnginx-mod-http-xslt-filter         1.14.2-2+deb10u5            amd64        XSLT Transformation module for Nginx
    ii  libnginx-mod-mail                     1.14.2-2+deb10u5            amd64        Mail module for Nginx
    ii  libnginx-mod-nchan                    1.14.2-2+deb10u5            amd64        Fast, flexible pub/sub server for Nginx
    ii  libnginx-mod-stream                   1.14.2-2+deb10u5            amd64        Stream module for Nginx
    ii  libp11-kit0:amd64                     0.23.15-2+deb10u1           amd64        library for loading and coordinating access to PKCS#11 modules - runtime
    ii  libpam-modules:amd64                  1.3.1-5                     amd64        Pluggable Authentication Modules for PAM
    ii  libpam-modules-bin                    1.3.1-5                     amd64        Pluggable Authentication Modules for PAM - helper binaries
    ii  libpam-runtime                        1.3.1-5                     all          Runtime support for the PAM library
    ii  libpam0g:amd64                        1.3.1-5                     amd64        Pluggable Authentication Modules library
    ii  libpcre2-8-0:amd64                    10.32-5+deb10u1             amd64        New Perl Compatible Regular Expression Library- 8 bit runtime files
    ii  libpcre3:amd64                        2:8.39-12                   amd64        Old Perl 5 Compatible Regular Expression Library - runtime files
    ii  libperl5.28:amd64                     5.28.1-6+deb10u1            amd64        shared Perl library
    ii  libpng16-16:amd64                     1.6.36-6                    amd64        PNG library - runtime (version 1.6)
    ii  libpopt0:amd64                        1.16-12                     amd64        lib for parsing cmdline parameters
    ii  libprocps7:amd64                      2:3.3.15-2                  amd64        library for accessing process information from /proc
    ii  libpsl5:amd64                         0.20.2-2                    amd64        Library for Public Suffix List (shared libraries)
    ii  libpython-stdlib:amd64                2.7.16-1                    amd64        interactive high-level object-oriented language (Python2)
    ii  libpython2-stdlib:amd64               2.7.16-1                    amd64        interactive high-level object-oriented language (Python2)
    ii  libpython2.7-minimal:amd64            2.7.16-2+deb10u4            amd64        Minimal subset of the Python language (version 2.7)
    ii  libpython2.7-stdlib:amd64             2.7.16-2+deb10u4            amd64        Interactive high-level object-oriented language (standard library, version 2.7)
    ii  libreadline7:amd64                    7.0-5                       amd64        GNU readline and history libraries, run-time libraries
    ii  librtmp1:amd64                        2.4+20151223.gitfa8646d.1-2 amd64        toolkit for RTMP streams (shared library)
    ii  libsasl2-2:amd64                      2.1.27+dfsg-1+deb10u2       amd64        Cyrus SASL - authentication abstraction library
    ii  libsasl2-modules-db:amd64             2.1.27+dfsg-1+deb10u2       amd64        Cyrus SASL - pluggable authentication modules (DB)
    ii  libseccomp2:amd64                     2.3.3-4                     amd64        high level interface to Linux seccomp filter
    ii  libselinux1:amd64                     2.8-1+b1                    amd64        SELinux runtime shared libraries
    ii  libsemanage-common                    2.8-2                       all          Common files for SELinux policy management libraries
    ii  libsemanage1:amd64                    2.8-2                       amd64        SELinux policy management library
    ii  libsepol1:amd64                       2.8-1                       amd64        SELinux library for manipulating binary security policies
    ii  libslang2:amd64                       2.3.2-2                     amd64        S-Lang programming library - runtime version
    ii  libsmartcols1:amd64                   2.33.1-0.1+deb10u1          amd64        smart column output alignment library
    ii  libsqlite3-0:amd64                    3.27.2-3+deb10u2            amd64        SQLite 3 shared library
    ii  libss2:amd64                          1.44.5-1+deb10u3            amd64        command-line interface parsing library
    ii  libssh2-1:amd64                       1.8.0-2.1+deb10u1           amd64        SSH2 client-side library
    ii  libssl1.1:amd64                       1.1.1n-0+deb10u6            amd64        Secure Sockets Layer toolkit - shared libraries
    ii  libstdc++6:amd64                      8.3.0-6                     amd64        GNU Standard C++ Library v3
    ii  libsystemd0:amd64                     241-7~deb10u10              amd64        systemd utility library
    ii  libtasn1-6:amd64                      4.13-3+deb10u1              amd64        Manage ASN.1 structures (runtime)
    ii  libtiff5:amd64                        4.1.0+git191117-2~deb10u9   amd64        Tag Image File Format (TIFF) library
    ii  libtinfo6:amd64                       6.1+20181013-2+deb10u5      amd64        shared low-level terminfo library for terminal handling
    ii  libudev1:amd64                        241-7~deb10u10              amd64        libudev shared library
    ii  libunistring2:amd64                   0.9.10-1                    amd64        Unicode string library for C
    ii  libuuid1:amd64                        2.33.1-0.1+deb10u1          amd64        Universally Unique ID library
    ii  libwebp6:amd64                        0.6.1-2+deb10u3             amd64        Lossy compression of digital photographic images.
    ii  libx11-6:amd64                        2:1.6.7-1+deb10u4           amd64        X11 client-side library
    ii  libx11-data                           2:1.6.7-1+deb10u4           all          X11 client-side library
    ii  libxau6:amd64                         1:1.0.8-1+b2                amd64        X11 authorisation library
    ii  libxcb1:amd64                         1.13.1-2                    amd64        X C Binding
    ii  libxdmcp6:amd64                       1:1.1.2-3                   amd64        X11 Display Manager Control Protocol library
    ii  libxml2:amd64                         2.9.4+dfsg1-7+deb10u6       amd64        GNOME XML library
    ii  libxpm4:amd64                         1:3.5.12-1+deb10u2          amd64        X11 pixmap library
    ii  libxslt1.1:amd64                      1.1.32-2.2~deb10u2          amd64        XSLT 1.0 processing library - runtime library
    ii  libxtables12:amd64                    1.8.2-4                     amd64        netfilter xtables library
    ii  libzstd1:amd64                        1.3.8+dfsg-3+deb10u2        amd64        fast lossless compression algorithm
    ii  localepurge                           0.7.3.5                     all          reclaim disk space by removing unneeded localizations
    ii  locales                               2.28-10+deb10u4             all          GNU C Library: National Language (locale) data [support]
    ii  login                                 1:4.5-1.1                   amd64        system login tools
    ii  lsb-base                              10.2019051400               all          Linux Standard Base init script functionality
    ii  mawk                                  1.3.3-17+b3                 amd64        a pattern scanning and text processing language
    ii  mime-support                          3.62                        all          MIME files 'mime.types' & 'mailcap', and support programs
    ii  mount                                 2.33.1-0.1+deb10u1          amd64        tools for mounting and manipulating filesystems
    ii  ncurses-base                          6.1+20181013-2+deb10u5      all          basic terminal type definitions
    ii  ncurses-bin                           6.1+20181013-2+deb10u5      amd64        terminal-related programs and man pages
    ii  net-tools                             1.60+git20180626.aebd88e-1  amd64        NET-3 networking toolkit
    ii  nginx-common                          1.14.2-2+deb10u5            all          small, powerful, scalable web/proxy server - common files
    ii  nginx-extras                          1.14.2-2+deb10u5            amd64        nginx web/proxy server (extended version)
    ii  openssl                               1.1.1n-0+deb10u6            amd64        Secure Sockets Layer toolkit - cryptographic utility
    ii  passwd                                1:4.5-1.1                   amd64        change and administer password and group data
    ii  perl                                  5.28.1-6+deb10u1            amd64        Larry Wall's Practical Extraction and Report Language
    ii  perl-base                             5.28.1-6+deb10u1            amd64        minimal Perl system
    ii  perl-modules-5.28                     5.28.1-6+deb10u1            all          Core Perl modules
    ii  procps                                2:3.3.15-2                  amd64        /proc file system utilities
    ii  psmisc                                23.2-1+deb10u1              amd64        utilities that use the proc file system
    ii  python                                2.7.16-1                    amd64        interactive high-level object-oriented language (Python2 version)
    ii  python-minimal                        2.7.16-1                    amd64        minimal subset of the Python2 language
    ii  python2                               2.7.16-1                    amd64        interactive high-level object-oriented language (Python2 version)
    ii  python2-minimal                       2.7.16-1                    amd64        minimal subset of the Python2 language
    ii  python2.7                             2.7.16-2+deb10u4            amd64        Interactive high-level object-oriented language (version 2.7)
    ii  python2.7-minimal                     2.7.16-2+deb10u4            amd64        Minimal subset of the Python language (version 2.7)
    ii  readline-common                       7.0-5                       all          GNU readline and history libraries, common files
    ii  runit                                 2.1.2-25                    amd64        system-wide service supervision
    ii  runit-helper                          2.8.6                       all          dh-runit implementation detail
    ii  sed                                   4.7-1                       amd64        GNU stream editor for filtering/transforming text
    ii  sensible-utils                        0.0.12                      all          Utilities for sensible alternative selection
    ii  sysuser-helper                        1.3.3                       all          dh-sysuser implementation detail
    ii  sysvinit-utils                        2.93-8                      amd64        System-V-like utilities
    ii  tar                                   1.30+dfsg-6+deb10u1         amd64        GNU version of the tar archiving utility
    ii  tzdata                                2024a-0+deb10u1             all          time zone and daylight-saving time data
    ii  ucf                                   3.0038+nmu1                 all          Update Configuration File(s): preserve user changes to config files
    ii  unzip                                 6.0-23+deb10u3              amd64        De-archiver for .zip files
    ii  util-linux                            2.33.1-0.1+deb10u1          amd64        miscellaneous system utilities
    ii  whiptail                              0.52.20-8                   amd64        Displays user-friendly dialog boxes from shell scripts
    ii  xtail                                 2.1-6                       amd64        like "tail -f", but works on truncated files, directories, more
    ii  zlib1g:amd64                          1:1.2.11.dfsg-1+deb10u2     amd64        compression library - runtime
