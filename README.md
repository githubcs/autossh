# autossh
Auto Login SSH Server (expect-based)

# Install

```
$ git clone https://github.com/wufeifei/autossh.git
$ sudo cp autossh/* /usr/local/bin/
```

# Config

```
$ cat ~/.autossh
192.168.1.110|root|password
wufeifei.com|root|password
```

# Usage

```
$ autossh
############################################################
#                     [AUTO SSH]                           #
#                                                          #
#                                                          #
# [1] 192.168.1.110:feei                                   #
# [2] 10.11.2.103:root                                     #
# [3] 103.21.140.84:root                                   #
#                                                          #
#                                                          #
############################################################
```
