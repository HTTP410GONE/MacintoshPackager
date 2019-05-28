# MacintoshPackager
Macintosh Packager - DPKG Alternative

## How to install
Paste these commands to Terminal.

FOR macOS: 
```curl -Ls https://raw.githubusercontent.com/HTTP410GONE/MacintoshPackager/master/gnet-live -o ~/netlive; chmod +x ~/netlive; sudo ~/netlive```

FOR Linux: 
```curl -Ls https://raw.githubusercontent.com/HTTP410GONE/MacintoshPackager/master/gnet-linux-live -o ~/netlive; chmod +x ~/netlive; sudo ~/netlive```


## Download from my private repo

FOR macOS: 
```curl -Ls http://repo.zeone.kro.kr/repo/net-live -o ~/netlive; chmod +x ~/netlive; sudo ~/netlive```

FOR Linux: 
```curl -Ls http://repo.zeone.kro.kr/repo/net-linux-live -o ~/netlive; chmod +x ~/netlive; sudo ~/netlive```


## MPACK repo
[My Private Repo](http://repo.zeone.kro.kr/repo)
[GitHub](https://github.com/HTTP410GONE/Macintosh-Packages)


## How to install unsupported packages
If the package you are trying to install is .mp (legacy and old, but installable with modern mpkg), then just change the extension to .mpack.

If the package you are trying to install conflicts with the OS architecture, then DO NOT INSTALL IT. Architecture limitation is there to protect your computer from installing wrong package, and the limiting feature is optional for developer, but when developer limited the certain architecture, then If you think the package supports different architecture but limited to install, contact to the developer.

## Sample Output after installation

>     Password:
>     NETINSTALL-LIVE
>     VERSION: 1.6
>     LAST UPDATE: MAY.29.2019 KST 00:10:20
>     This will install:
>     mpkg 5.1 Duo
>     net 1.1
>     Checking architecture...
>     Downloading files...
>     Running Macintosh Packager-live...
>     Last Update: May 5, 2019 KST 15:38:20
>     BASE: MPKG 1.2
>     MPKG 4.3 SEMI-COMPATIBILITY LAYER INCLUDED
>     Locking mpkg...
>     Unpacking...
>     Installing Macintosh Packager...
>     Selecting mpkg 5.1duo to install...
>     Removing Finder Elements...
>     Installing...
>     Running postinst...
>     Installing controls...
>     Writing connected files to database...
>     Analysis written to database.
>     Finished installing: Macintosh Packager 5.1duo
>     Cleaning up...
>     Running Macintosh Packager-live...
>     Last Update: May 5, 2019 KST 15:38:20
>     BASE: MPKG 1.2
>     MPKG 4.3 SEMI-COMPATIBILITY LAYER INCLUDED
>     mkdir: /usr/local/mpkglib: File exists
>     Locking mpkg...
>     Unpacking...
>     Installing Net Install...
>     Selecting com.zeone.netinstall 1.1 to install...
>     Removing Finder Elements...
>     Installing...
>     Installing controls...
>     Writing connected files to database...
>     Analysis written to database.
>     Finished installing: Net Install 1.1
>     Cleaning up...
>     Done.
