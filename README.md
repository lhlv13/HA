# HA
![homeassistant](./readmeImg/homeassistant.png)

<b>非公開筆記 : </b>
<ul>
  <li><a href="https://hackmd.io/KGeOe7OfSJSMwnYqckX34w">Docker 觀念篇</a></li>
  <li><a href="https://hackmd.io/gIsnpqEmQAuCRYOTGBoZFw">Docker 實作篇</a></li>
</ul>
---

## Docker 安裝
* <b>卸載舊版本Docker</b>
```
$ sudo apt-get remove docker docker-engine docker.io containerd runc
```

* <b>安裝Docker</b>
```
$ sudo apt-get update && sudo apt-get upgrade
```

```
$ curl -sSL https://get.docker.com | sh​
```
![](https://i.imgur.com/yVi6DDW.png)


### 安裝後續
* <b>讓非root也可使用</b>
```
$ sudo usermod -aG docker pi
```

* <b>查看版本</b>
```
$ docker -v
```
![](https://i.imgur.com/en9hNiG.png)


* <b>重啟</b>
```
$ sudo reboot
```
