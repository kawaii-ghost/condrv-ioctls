# condrv-ioctls
List of ConDrv IOCTL code

| IOCTL                               	| Hex Value 	| Desc                                      	|
|-------------------------------------	|-----------	|-------------------------------------------	|
| `IOCTL_CONDRV_READ_IO`               	| 0x500006  	|                                           	|
| `IOCTL_CONDRV_COMPLETE_IO`            	| 0x50000b  	|                                           	|
| `IOCTL_CONDRV_READ_INPUT`             	| 0x50000f  	|                                           	|
| `IOCTL_CONDRV_WRITE_OUTPUT`           	| 0x500013  	|                                           	|
| `IOCTL_CONDRV_ISSUE_USER_IO`          	| 0x500016  	| Almost of all Console APIs use this IOCTL 	|
| `IOCTL_CONDRV_DISCONNECT_PIPE`        	| 0x50001b  	|                                           	|
| `IOCTL_CONDRV_SET_SERVER_INFORMATION` 	| 0x50001f  	|                                           	|
| `IOCTL_CONDRV_GET_SERVER_PID`         	| 0x500023  	| Used by AttachConsole and FreeConsole     	|
| `IOCTL_CONDRV_GET_DISPLAY_SIZE`       	| 0x500027  	|                                           	|
| `IOCTL_CONDRV_UPDATE_DISPLAY`         	| 0x50002b  	|                                           	|
| `IOCTL_CONDRV_SET_CURSOR`             	| 0x50002f  	|                                           	|
| `IOCTL_CONDRV_ALLOW_VIA_UIACCESS`     	| 0x500033  	|                                           	|
| `IOCTL_CONDRV_LAUNCH_SERVER`          	| 0x500037  	| Used by AllocConsole                      	|
| `IOCTL_CONDRV_GET_FONT_SIZE`          	| 0x50003b  	|                                           	|

Not using IOCTL : `ClosePseudoConsole`, `CreatePseudoConsole`, `GetStdHandle`, `ResizePseudoConsole`,

`SetConsoleCtrlHandler`, `SetConsoleDisplayMode`, `SetStdHandle`.
