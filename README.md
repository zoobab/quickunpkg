EXAMPLE
=======

$ quickunpkg portage-utils-0.10.tbz2

DEPENDENCIES
============

app-portage/portage-utils

SCREENSHOT
==========
    
    * 12:40 root@gentoo3 /usr/portage/packages/app-portage# quickunpkg portage-utils-0.10.tbz2 
    ================================================================
    Create the workdir, tbz2file
    ================================================================
    TBZ2FILE=portage-utils-0.10.tbz2
    TBZ2FILE_XPAK=portage-utils-0.10.xpak
    WORKDIR=/tmp/20120914_124009
    mkdir: created directory `/tmp/20120914_124009'
    ================================================================
    Copying the file to the workdir
    ================================================================
    `portage-utils-0.10.tbz2' -> `/tmp/20120914_124009/portage-utils-0.10.tbz2'
    ================================================================
    Uncompressing the tbz2file
    ================================================================
    input tbz2: portage-utils-0.10.tbz2 (664.1k)
    output tar.bz2: (null) (641.8k)
    output xpak: portage-utils-0.10.xpak (22.3k)
    PF=portage-utils-0.10
    CATEGORY=app-portage
    TBZ2FILE_XPAK=portage-utils-0.10.xpak
    ================================================================
    Emerging portage-utils-0.10.tbz2
    ================================================================
    mkdir: created directory `/tmp/20120914_124009/All'
    `portage-utils-0.10.tbz2' -> `/tmp/20120914_124009/All/portage-utils-0.10.tbz2'
    
     * IMPORTANT: 3 news items need reading for repository 'gentoo'.
     * Use eselect news to read news items.
    
    Calculating dependencies... done!
    
    >>> Emerging binary (1 of 1) app-portage/portage-utils-0.10
     * portage-utils-0.10.tbz2 size ;-) ...                                  [ ok ]
    >>> Extracting info
    >>> Extracting app-portage/portage-utils-0.10
    
    >>> Installing (1 of 1) app-portage/portage-utils-0.10
     * /etc/portage/postsync.d/q-reinitialize has been installed for convenience
     * If you wish for it to be automatically run at the end of every --sync:
     *    # chmod +x /etc/portage/postsync.d/q-reinitialize
     * Normally this should only take a few seconds to run but file systems
     * such as ext3 can take a lot longer.  To disable, simply do:
     *    # chmod -x /etc/portage/postsync.d/q-reinitialize
    
    >>> Recording app-portage/portage-utils in "world" favorites file...
    
     * Messages for package app-portage/portage-utils-0.10:
    
     * /etc/portage/postsync.d/q-reinitialize has been installed for convenience
     * If you wish for it to be automatically run at the end of every --sync:
     *    # chmod +x /etc/portage/postsync.d/q-reinitialize
     * Normally this should only take a few seconds to run but file systems
     * such as ext3 can take a lot longer.  To disable, simply do:
     *    # chmod -x /etc/portage/postsync.d/q-reinitialize
    >>> Auto-cleaning packages...
    
    >>> No outdated packages were found on your system.
    
     * Regenerating GNU info directory index...
     * Processed 94 info files.
    
     * IMPORTANT: 3 news items need reading for repository 'gentoo'.
     * Use eselect news to read news items.
    
