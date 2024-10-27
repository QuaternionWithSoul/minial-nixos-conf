### This is the minimum change to make my "nixos-config" setup work later
Change the user name, host name, system version (to the current one). If necessary, change networking.

If needed add
boot.loader.efi.efiSysMountPoint = "/boot/efi";
to hardware-configuration.nix
