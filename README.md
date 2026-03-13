# Digital Forensics Disk Recovery Cases

This repository presents practical digital forensics case studies focused on recovering damaged disk structures and restoring inaccessible evidence through manual forensic analysis.

## Repository Scope

The cases demonstrate recovery techniques applied to corrupted partition metadata in both MBR and GPT disk structures using hex-level examination and forensic validation tools.

## Included Case Studies

### Case 01 — Forensic Recovery of Corrupted GPT Disk Structures

Restoration of a damaged Protective MBR and Primary GPT Header using backup GPT structures stored at the end of the disk.

**Recovered evidence:**

### Case 02 — Forensic Analysis and Recovery of Corrupted MBR Disk Structures

Recovery of an intentionally damaged MBR-based disk after overwriting the first 1024 bytes, followed by manual NTFS identification and evidence recovery.

**Recovered evidence:**

* Simulated visual evidence representing inappropriate content (cat image)
* Hidden text evidence containing a secret message

### Case 03 — Forensic Repair of a Damaged MBR Partition Table

Manual reconstruction of a corrupted MBR partition entry by restoring boot indicator, CHS values, partition type, LBA start, and total sector count.

**Recovered evidence:**

* Secret text file successfully recovered after partition repair

## Tools Used

* 010 Editor
* FTK Imager
* Hex templates
* Manual LBA calculations

## Skills Demonstrated

* MBR repair
* GPT reconstruction
* Partition table recovery
* NTFS signature analysis
* Manual sector calculations
* Evidence recovery

## Purpose

These cases were developed as practical forensic exercises to demonstrate low-level disk recovery techniques used when automated forensic tools cannot interpret damaged metadata.
