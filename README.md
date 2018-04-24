# GitLab for docker-compose

## ADD SSH KEY CONFIG

.ssh/config

```
Host <HOSTNAME>
    HostName <SERVER_ADDRESS>
    User git
    Port 8022
```

`<HOSTNAME>`にdocker-compose.ymlでhostnameに指定したものを書く  
`<SERVER_ADDRESS>`は動かしているサーバーのドメイン or IPアドレスを記述

