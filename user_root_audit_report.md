# User Root Directory Audit Report
Generated: 2025-08-28

## Executive Summary
Total user directory size: ~82 GB across 52 items

## Major Space Consumers

### Top Directories by Size
1. **Mylio** – 31.00 GB (Photo management application)
2. **AppData** – 27.29 GB (Application data and settings)
3. **Downloads** – 15.68 GB (Downloaded files)
4. **Documents** – 2.26 GB (User documents)
5. **.Mylio_Catalog** – 2.22 GB (Mylio catalog data)

### Largest Individual Files
1. **VeeamBackup ISO** – 12.89 GB (`~\Downloads\VeeamBackup&Replication_12.3.2.3617_20250610.iso`)
2. **WSL Virtual Disk** – 3.2 GB (`~\AppData\Local\wsl\*\ext4.vhdx`)
3. **CachyOS ISO** – 2.77 GB (`~\Downloads\cachyos-desktop-linux-250713.iso`)
4. **NVIDIA DXCache** – 2.00 GB (`~\AppData\Local\NVIDIA\DXCache\065ba91cb4323070.nvph`)
5. **Gmail Archive** – 1.29 GB (Thunderbird email cache)

## Cache and Temporary Files Analysis

### Identified Cache Locations
- **Windows Temp** – 1.88 GB (`~\AppData\Local\Temp`)
- **Edge Browser Cache** – 0.40 GB
- **Windows Packages** – 6.06 GB (`~\AppData\Local\Packages`)
- **Web Cache** – 0.04 GB
- **Internet Cache** – Minimal (0.05 MB)

**Total Cache/Temp**: ~8.38 GB

## Hidden Files and Folders
- **Total Hidden Files Size**: 13.91 MB
- **Key Hidden Items**:
  - `.claude.json` and backup – 3.68 MB
  - Windows user registry files (`NTUSER.DAT`) – 6.25 MB
  - Various shell configuration files (`.bashrc`, `.gitconfig`, etc.)
  - Application directories (`.bun`, `.npm-global`, `.vscode`, `.ssh`)

## Recommendations for Cleanup

### Immediate Actions (Potential Space Savings: ~25 GB)
1. Remove old ISO files in Downloads folder (15.66 GB)
   - VeeamBackup ISO (12.89 GB)
   - CachyOS ISO (2.77 GB)
2. Clear Windows Temp folder (1.88 GB)
   - `~\AppData\Local\Temp`
3. Clean browser caches (0.40 GB)
   - Edge cache
4. Review NVIDIA DXCache (≈2.00 GB)
   - Large shader cache files can be cleared

### Medium Priority
1. Review Mylio data (31.00 GB)
   - Consider moving to external storage if not actively used
2. Clean Windows Packages (6.06 GB)
   - Review and remove unused Windows Store apps
3. Optimize WSL (3.20 GB)
   - Compact the WSL virtual disk if not in use

### Low Priority
1. Email archives (1.29 GB)
   - Archive old Thunderbird emails to external storage
2. Review Documents folder (2.26 GB)
   - Archive old projects and documents

## System Organization Notes

### Well-Organized Areas
- Development files consolidated in `Documents/dev/`
- Clear separation of configuration files (dotfiles)
- Proper use of hidden directories for application data

### Areas Needing Attention
- Large ISO files in Downloads should be moved or deleted
- Consider implementing automatic temp file cleanup
- Review and organize the Mylio photo library

## Summary Statistics
- **Total Directories**: 37 visible + 15 hidden
- **Total Files in Root**: 16 visible + numerous hidden system files
- **Largest Single File**: 12.89 GB (Veeam ISO)
- **Smallest Directory**: Multiple empty directories (0 MB)
- **Cache/Temp Data**: ~8.38 GB (≈10% of total)
- **Potential Easy Cleanup**: ~25 GB (≈30% of total)

## Action Items
1. Delete or move ISO files from Downloads
2. Run disk cleanup for temporary files
3. Clear browser caches
4. Review and compact WSL if not actively used
5. Consider external storage for Mylio library
6. Set up a regular maintenance schedule for cache cleanup
