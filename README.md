# zhangsanya321-loon

Loon 插件库。

## 本机开发服务回环

Loon 3.5.3(1007)+：将开发服务 IP 10.7.0.1 拉入 TUN 并反射回环，Loon 开启时也能访问本机服务（SideStore 续签用）。

### 一键添加到 Loon（在 iPhone / iPad 上点）

[一键添加到 Loon](https://www.nsloon.com/openloon/import?plugin=https%3A%2F%2Fraw.githubusercontent.com%2Fshizhangsanya321%2Fzhangsanya321-loon%2Fmain%2Fdev-loopback.plugin)

点上面这个链接会自动跳到 Loon 并导入插件，确认后开启即可。

直接用 Loon URL Scheme 的链接（部分 App 里可点）：

[loon://import?plugin=...](loon://import?plugin=https%3A%2F%2Fraw.githubusercontent.com%2Fshizhangsanya321%2Fzhangsanya321-loon%2Fmain%2Fdev-loopback.plugin)

### 手动添加（上面一键点不开时用）

Loon → 插件 → 添加远程插件，粘贴：

https://raw.githubusercontent.com/shizhangsanya321/zhangsanya321-loon/main/dev-loopback.plugin

## 插件列表

- dev-loopback.plugin：本机开发服务回环（include-tun = 10.7.0.1/32，10.7.0.1 = reflect）
