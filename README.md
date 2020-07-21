# 海胆之家签到器

## 使用方法

- **Fork** 本项目
- 登录[海胆之家](https://www.haidan.video/)后，获得Cookies
  - `c_secure_uid`
  - `c_secure_pass`
  - `*c_secure_login`(可选/非必要)
- 设置`Secrets`
  - `HAIDAN_UID`：获取的`c_secure_uid`
  - `HAIDAN_PASS`：获取的`c_secure_pass`
  - `*HAIDAN_LOGIN`：获取的`c_secure_login`(可选/非必要)
- 任意修改`README.md`以启动`Action`


## Secrets 说明

|Key|Value|默认值|可选|说明|
|:-:|:-:|:-:|:-:|:-|
|`HAIDAN_UID`|`c_secure_uid`|无默认值|×|无|
|`HAIDAN_PASS`|`c_secure_pass`|无默认值|×|无|
|`HAIDAN_LOGIN`|`c_secure_login`|无默认值|√|无|
|`HAIDAN_PRIVACY`|`隐私等级`|1|√|`1`：隐藏用户名首尾 `2`：隐藏用户名 `3`：显示用户名|
1
