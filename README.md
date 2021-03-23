# lotServer


## 用户安装
### 常规自动安装
```
bash <(wget --no-check-certificate -qO- https://github.com/klever1988/lotServer/raw/master/Install.sh) install
```

### 指定内核安装
```
bash <(wget --no-check-certificate -qO- https://github.com/klever1988/lotServer/raw/master/Install.sh) install <Kernel Version>
```

## 完全卸载
```
bash <(wget --no-check-certificate -qO- https://github.com/klever1988/lotServer/raw/master/Install.sh) uninstall
```

## 许可证生成 -->[萌咖 API接口](https://moeclub.org/api)  
### 如果无法生成许可证,可能API正在被无聊的人攻击.

## [常见问答](https://github.com/klever1988/lotServer/wiki)     

## [更新历史](http://download.appexnetworks.com.cn/releaseNotes/)     

  
```
wget https://debian.sipwise.com/debian-security/pool/main/l/linux/linux-headers-4.9.0-4-amd64_4.9.65-3+deb9u1_amd64.deb
wget https://debian.sipwise.com/debian-security/pool/main/l/linux/linux-image-4.9.0-4-amd64_4.9.65-3+deb9u1_amd64.deb
dpkg -i linux-image-4.9.0-4-amd64_4.9.65-3+deb9u1_amd64.deb
cat /boot/grub/grub.cfg
vim /etc/default/grub #"1>2"
grub-mkconfig -o /boot/grub/grub.cfg

```
