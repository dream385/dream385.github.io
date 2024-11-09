# Shadowrocket

## 下载地址

<a href="https://apps.apple.com/app/id932747118"><img width="200px" alt="Download on App Store" src="https://logos-download.com/wp-content/uploads/2016/06/Download_on_the_App_Store_logo.png"/></a>  

## 机场订阅

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/1.webp" width="900">


## 配置使用

<!-- prettier-ignore -->
!!! 注意
    以下操作应在导入节点，并开启Shadowrocket后进行

### 导入配置文件

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/2.webp" width="900">

复制以下配置链接，打开 **Shadowrocket**

```
https://gitlab.com/Nessk/vpn/-/raw/main/Shadowrocket/Shadowrocket.conf
```

点击底部工具栏 **配置** - **添加配置** - 填入链接并下载

点击 **本地文件** - **Shadowrocket.conf** - **使用配置**

### 检查规则集文件

点击 **Shadowrocket.conf** 右边的 **`ⓘ`** 图标

点击 **规则集URL** ，确保都下载成功（有绿色`√`）


<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/3.webp" width="900">

<!-- prettier-ignore -->
!!! 提示
    如有下载失败的，可点击该链接再次下载

### 设置分流分组

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/4.webp" width="900">

首页下拉即可进入 **代理分组** , 根据自己需求选择分流模式(无特殊需求可不更改，首页选择节点即可)




### 添加**GeoLite2**订阅

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/5.webp" width="600">


点击底部工具栏 **设置** ，点击下方 **Geolite2数据库**

在 **国家** 模块中的URL填入以下地址 ，并更新

- [Masaiki](https://github.com/Masaiki/GeoIP2-CN)(中国`IPv4`&`IPv6`)：

```
https://github.com/Masaiki/GeoIP2-CN/raw/release/Country.mmdb
```


</details>

## 证书设置

<!-- prettier-ignore -->
!!! 警告
    安装证书后，如更换配置文件，须重新执行以下步骤

### 生成证书

点击底部工具栏 **配置** ，点击刚才下载的配置右边的 **ⓘ** 图标

点击 **HTTPS解密** ，开启 **HTTPS解密** ，生成 **新的CA证书**

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/6.1.webp" width="1200">

### 安装证书

点击 **安装证书** ，点击 **允许** ，选择 iPhone

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/6.2.webp" width="900">



系统设置中，点击 **已下载描述文件** ，点击 **安装** 

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/6.3.webp" width="900">

### 信任证书


系统设置→通用中，点击最下方 **证书信任设置** ，勾选刚才安装的证书 

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/6.4.webp" width="1200">

## 安装模块

<!-- prettier-ignore -->
!!! 警告
    模块功能大多依赖于 [证书设置](../shadowrocket/index.md?#_7) 中安装信任的根证书


底部工具栏 **配置** → **模块** → 右上角 `➕`

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/shadowrocket/Photo/7.webp" width="600">

<details>
  <summary> 资源路径需要填写资源的raw格式链接，点此查看教程</summary>

以下方的链接举例(这是个网页，不是真正能使用的资源链接)：

```
https://github.com/blackmatrix7/ios_rule_script/blob/master/rule/QuantumultX/12306/12306.list
```

例如在末尾添加`?raw=ture`：

```
https://github.com/blackmatrix7/ios_rule_script/blob/master/rule/QuantumultX/12306/12306.list?raw=ture
```

或者直接点击`raw`或者`view`，⁠使用跳转后的链接：

```
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/12306/12306.list
```

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/quantumultx/Photo/raw1.webp" >

<img src="https://gitlab.com/Nessk/vpn/-/raw/main/blog/docs/quantumultx/Photo/raw2.webp" >



或者将链接里的`blob`⁠修改为`raw`：

```
https://github.com/blackmatrix7/ios_rule_script/raw/master/rule/QuantumultX/12306/12306.list
```



</details>





