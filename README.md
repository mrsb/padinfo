# padinfo
Create pad info from synced ISOs for use when Mageia ISO testing

To use
======

Drop into ~/bin and make it executable

`chmod +x ~/bin/padinfo`

For help..

`padinfo -h`


Example output
--------------

    $ padinfo -p ~/ISOs/Mageia5 -c
    ==================== Classic ISOs ====================



    Mageia-5-dual-DVD
    --------------------------------------------------
    ISO Name: Mageia-5-dual-DVD.iso
    DATE.txt: Tue May  5 01:25:05 CEST 2015
    md5sum:   17004194688bc03bd80ae01bcf1da331
    sha1sum:  e284edf2081f9d53f20ed73e71e52c5a1d288999

    Boot options:-
    F1 help    : 
    F2 language: 
    F3 800x600 : 
    F4 CD-ROM  : 
    F5 Driver  : 
    F6 Kernel Option: 

    Boot from hard disk: 
    Rescue : 
    Memtest: 
    HDT    : 
    (Hardware Detection Tool)



    Installer issues:-
    32bit:


    64bit:


    XFCE Install:-
    32bit:


    64bit:


    After Install and reboot:-
    32bit:


    64bit:


    Upgrade install:-


    ...etc.

