# Windows Commands

## Change ip

```
> netshh interface ipv4 set address name="Ethernet" static 169.254.61.157 255.255.0.0
```

## Remove temporarly Windows expiration delay

```
slmgr/rearm
```

## Remove temporarly Windows XP expiration delay

```
rundll32.exe syssetup,SetupOobeBnk
```
