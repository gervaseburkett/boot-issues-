# boot-issues-
Basic boot commands used to check and manage windows pcs

## 🚀 Top 10 Boot Commands
```sh
bootrec /fixmbr            # Fixes Master Boot Record
bootrec /fixboot           # Writes a new boot sector
bootrec /scanos            # Scans for Windows installations
bootrec /rebuildbcd        # Rebuilds the Boot Configuration Data
bcdedit /set {default} safeboot minimal  # Boot into Safe Mode
sfc /scannow               # System File Checker
chkdsk C: /f /r            # Check disk for errors and fix them
DISM /Online /Cleanup-Image /RestoreHealth  # Repairs system image
bcdedit /export C:\BCD_Backup  # Backup current BCD settings
shutdown /r /o             # Restart into advanced boot options
bcdboot [path]             # bcdboot (Boot Configuration Data Boot) command sets up a system partition by copying BCD files into an empty partition
arp -a                    # The arp (Address Resolution Protocol) command shows and modifies entries in the ARP cache. The cache contains one or multiple tables that map IP addresses to physical (MAC) addresses for devices on the local network
```
