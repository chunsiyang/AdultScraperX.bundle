# AdultScraperX 
### AdultScraperX是一个可以匹配成人影片信息的插件(不提供任何影片下载与观看连接)，仅提供简介、演员、标题、类型、系列、导演、工作室的信息匹配。
使用帮助
- AdultScraperX 需要配合 AdultScraperX-server 一起试用

- 本地字幕挂载：
需要在代理中勾选：Local Media Assets (Movies)
- plex目录标记设置： 
```
1、欧美与日本(骑兵、步兵、动漫)的主目录标记可以在插件中自定义配置
2、配置目录标记:必须含有(前、后)特殊字符如：-M- 、*M*、=M=以此类推
3、主目录标记只可出现一次，并且与主目录文件夹名的标记一致才可识别
```
### TG群：https://t.me/AdultScraperX

### AdultScraperX-server 服务端项目地址 
- https://github.com/chunsiyang/AdultScraperX-server

### 命名规范：

#### 日本骑兵：

- 项目列表标准番号.mp4  (优选)

- 项目列表任意字符与标准番号.mp4 

#### 日本步兵：

- 标准番号.mp4  (优选)
- 任意字符与标准番号.mp4  

#### 日本动漫
- 标准番号.mp4  (优选)
- 任意字符与标准番号.mp4 

#### 欧美：
- 工作室 - 片名 - 明星（可以包含多个）.mp4 

#### 同片多版本或多CD的命名方法：
- 命名-vol1.mp4
- 命名-vol2.mp4

### 插件配置说明
- Plex Plugin 服务端参数配置
```
- API服务URL ：服务端地址（填写时需包含 http://或https://头）
- API服务Port ： 服务端端口
```
- 使用缓存或开启用户权限时才需要填写下列配置，群晖Docker用户群体无需填写。
```
个人DDNS ：plex所使用的公网域名或固定IP地址
Plex端口 ：plex所使用的端口
令牌 ： 访问服务端的令牌
```
