# Investigation Summary

## FAT32

I examined a FAT32 forensic disk image using The Sleuth Kit and Autopsy. The investigation covered the partition layout, FAT tables, root directory entries, cluster allocation, file metadata and deleted-file recovery. I used tools including `mmls`, `fsstat`, `fls`, `istat`, `icat` and `blkcat` to compare results and verify findings.

## NTFS

I examined an NTFS forensic disk image with a focus on the Master File Table. I reviewed `$MFT` and `$MFTMirr`, inspected file metadata and timestamps, and compared resident and non-resident data. I also manually decoded an MFT entry in a hex editor, identifying the `FILE` signature and the `$STANDARD_INFORMATION`, `$FILE_NAME` and `$DATA` attributes.

## Repository Scope

Only a short summary and redacted screenshots are included. Original assessment documents, disk images, recovered evidence and personal information are intentionally excluded.
