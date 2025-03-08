# Router Configuration Commands

## Giving hostname to the router:

```
router(config)#hostname R1
R1(config)#
```

## Banner MOTD:

```
router(config)#banner motd #
Enter Text message. End with character '#'
$ No unauthorized access allowed. Enter your credentials!! #
```

## Setting password:

### 1. Enable password:

```
router(config)#enable password 12345678
```

### 2. Enable secret password:

```
router(config)#enable secret 12345678
```

### 3. Line console password:

```
router(config)#line console 0
router(config-line)#password 12345678
router(config-line)#login
```

### 4. Line VTY password:

```
router(config)#line VTY 0 4
router(config-line)#password 12345678
router(config-line)#exit
```

## Assigning IP address to a router’s interface:

```
router(config)#interface fa0/0
router(config-if)#ip address 192.168.1.1 255.255.255.0
router(config-if)#no shut
```

## Copying and erasing configuration:

```
router#copy running-config startup-config
router#erase startup-config
```
