**MBR (Master Boot Record)** is a legacy partitioning scheme used to manage disk partitions and boot operating systems on traditional BIOS-based systems. Here are the key features:

### Key Features

1. **Partition Structure**:
   - MBR supports up to four primary partitions or three primary partitions and one extended partition that can contain multiple logical partitions.

2. **Boot Information**:
   - The first sector of the disk contains boot code that is executed when the system starts, leading to the operating system loader.

3. **Disk Size Limitation**:
   - MBR can handle disks up to 2 TB in size, which can be limiting for modern storage needs.

4. **File System Compatibility**:
   - MBR is compatible with various file systems, including FAT32, NTFS, and ext4.

### Limitations

- **Partition Limits**: The limitation of four primary partitions can be restrictive for complex setups.
- **Size Limitation**: Inability to manage disks larger than 2 TB.
- **BIOS Dependency**: MBR is used primarily with BIOS firmware, which is being replaced by UEFI in modern systems.

### Conclusion

MBR is an older but foundational partitioning scheme still found in some systems, especially those using traditional BIOS. However, it has largely been superseded by **GPT (GUID Partition Table)** in newer systems due to its limitations.