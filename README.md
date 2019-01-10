# Custom iPXE 

Quick start guide:

The file "undionly.kpxe" is custom build image to chain boot with PXELINUX

You can customize by editing the file src/preboot.ipxe with appropriate commands as per your requirement and execute the following commands.

```
   cd src
   make bin/undionly.kpxe EMBED=preboot.ipxe
```

UEFI supported ROM image 

```
   cd src
   make bin-x86_64-efi/ipxe.efi EMBED=preboot.ipxe
```

For any more detailed instructions, see http://ipxe.org
