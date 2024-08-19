# nx-ovlloader
Host process for loading Switch overlay OVLs (NROs)

This is the loader service of the Tesla ecosystem. It's derrived from the default nx-hbloader.
When being run, this service automatically tries to chainload `/switch/.overlays/ovlmenu.ovl`, the Tesla Menu. From there on it will load and switch between different overlays on request. 

# nx-ovlloader+
(Built with expanded memory for Overlay power users)


# Sidenote
**nx-ovlloader+** consumes more of the available system memory than the base loader. That could impact your system depending on how much memory your setup currently consumes.
