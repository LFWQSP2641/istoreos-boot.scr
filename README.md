# istoreos-boot.scr
构建 FriendlyElec NanoPi R3S 的 boot.scr ，用于修复 RTL8811CU "0bda:1a2b not switching to c811, Switching works only when re-plugged."。

参见 https://www.draisberghof.de/usb_modeswitch/bb/viewtopic.php?t=3055 。

修改：添加内核启动参数 `usb-storage.quirks=0bda:1a2b:i`
