# 0xD823 MaxRecordableTime

### Device Prop Code

0xD823

### Overview

Acquires or sets the maximum shooting time (sec) of the camera.  
(Vendor Extension Property)

### Support model

| X | Z1 | V | SC | S |
|:--|:--|:--|:--|:--|
| All | All | All | --- | --- |

### Support value

300, 1500, 7200 (*1)

(*1) THETA X Version 2.00.0 or later, only for 5.7K 2/5/10fps and 8K 2/5/10fps.  
If you set 7200 seconds in 8K 10fps mode and then set back to 4K 30fps mode, the max recordable time will be overwritten to 1500 seconds automatically.
