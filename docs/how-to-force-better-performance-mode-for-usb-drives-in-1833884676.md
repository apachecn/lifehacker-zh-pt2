# 如何在 Windows 10 中强制 USB 驱动器进入“更高性能”模式

> 原文：<https://lifehacker.com/how-to-force-better-performance-mode-for-usb-drives-in-1833884676>

随着最新的 Windows 10 更新， [Windows 10 1809](https://docs.microsoft.com/en-us/windows/whats-new/whats-new-windows-10-version-1809) ，微软已经改变了默认的 USB 驱动器传输设置，以支持快速移除而不是更好的性能。



虽然自 Windows 7 以来，“快速删除”一直是某些驱动器格式(如 FAT32)的默认策略，但 Window 10 1809 更新现在使其成为所有驱动器格式的默认策略，包括 NTFS 和 exFAT。一些格式以前默认为“更好的性能”，即缓存对 USB 驱动器的写操作以获得更好的系统性能，但这些缓存的传输必须在移除驱动器之前完成，以防止丢失数据，因此有了“安全移除”选项。有了这一改变，用户将不再需要在从他们的 PC 上拔出 USB 设备之前选择“安全移除 USB 设备”,至少在默认情况下是如此。

虽然有人担心将“快速移除”作为默认策略会降低 USB 设备的性能，但这实际上可能是一件好事，因为它可以防止过早移除驱动器时出现拙劣的传输。但是，如果您确实遇到性能下降，或者只是喜欢手动选择安全移除硬件的过程，以下是如何将驱动器改回“更好的性能”

*   将 USB 存储设备插入您的 Windows PC。
*   打开文件资源管理器，然后转到**这台电脑**，记下您的设备的驱动器号(如“USB 驱动器(C:)”)。
*   打开开始菜单，然后在搜索栏中键入“磁盘管理”，或者右击**开始菜单>磁盘管理。**
*   在磁盘管理器窗口的下半部分找到您的驱动器，右键单击其名称并转到**属性>** **策略**
*   选择您希望更改为“更好性能”的策略
*   选中“在此设备上启用写缓存”旁边的框