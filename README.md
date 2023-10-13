# vcpkg_install_notes
vcpkg使用问题及解决方案记录


### 网络问题
windows的powershell临时使用代理
```powershell
$env:http_proxy="http://127.0.0.1:10809"
$env:https_proxy="socks://127.0.0.1:10808"
```
