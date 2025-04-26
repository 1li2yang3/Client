# QtTalk

## 项目简介

QtTalk 是一个使用 **Qt + C++** 开发的桌面聊天客户端，支持基本的文字消息发送与显示，拥有联系人管理、好友申请、聊天记录气泡展示等功能。

## 技术栈

- **开发语言**：C++
- **图形界面**：Qt
- **项目结构**：面向对象设计，模块化开发
- **主要功能模块**：
  - 聊天界面
  - 联系人管理
  - 好友申请与验证
  - 消息输入框优化化


## 文件结构

- `BubbleFrame.*`、`ChatItemBase.*`：气泡式消息框
- `chatdialog.*`、`chatpage.*`：聊天窗口、聊天页面
- `contactuserlist.*`、`conuseritem.*`：联系人列表与展示
- `applyfriend.*`、`authenfriend.*`：好友申请与验证界面
- `MessageTextEdit.*`、`customizetextedit.*`：自定义文本输入框
- `static/`, `style/`, `res/`：资源文件夹（图片、样式等）

  
#界面仿照微信客户端，提供登录、注册、邮箱验证、聊天等功能，支持文字、图片等消息格式。
![image](https://github.com/1li2yang3/WeiXing_Client/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE.png)




