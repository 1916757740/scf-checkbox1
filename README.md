# <center>关于项目</center>

## 作者库同步并部署到腾讯云函数功能介绍：

### 定时同步作者的代码到私人库并触发部署到腾讯云函数；
### 同步并部署1次，手动同步代码触发部署;

## 注意事项：
### main.yml文件所在分支要设置为默认分支，并且不能为master分支，我用的是main分支；（master用来放作者库）
### 使用到的环境变量：
| Name                          |   归属                  | 属性        |
| :---------------------:       | :----------:           | --------- | 
| `PAT`                         |Personal access token   | 必须 | 
| `TENCENT_SECRET_ID`           |腾讯云访问密钥id           | 必须 | 
| `TENCENT_SECRET_KEY`          |腾讯云访问密钥secret       | 必须 | 
| `DEPLOY_TG_BOT_TOKEN`         |telegram推送             | 非必须 |
| `DEPLOY_TG_USER_ID`           |telegram推送             | 非必须 |
| `DEPLOY_PUSH_KEY`             |微信server酱推送          | 非必须 |

### 详细部署教程(建议看这个文章)地址：[涅槃重生：零基础玩转云函数之签到盒](https://www.llh1347.com/archives/2022409.html)
![image](https://user-images.githubusercontent.com/68180007/162554127-5501cc84-3a42-4adc-a8dd-17328305dcda.jpeg)

## 喜欢本项目的欢迎点star⭐️和fork，谢谢♥~
- 2022.4.14更新 感谢网名为恶意的群友在使用本项目并提出问题，问题目前已经修复。

## 特别感谢(排名不分先后)
- @忧郁的未来-群友
- @恶意-群友
- [@wenmoux](https://github.com/wenmoux/checkbox)
- [@wenyanY](https://github.com/wenyanY)
