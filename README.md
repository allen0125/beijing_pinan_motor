# 北京平安平价三者险商业险预约

本项目旨在帮助用户预约北京平安平价三者险商业险。项目使用Python开发，严禁倒卖和用于牟利。如果发现此类行为，请及时举报，谢谢。

## 温馨提示

请注意，第三方代抢服务可能需要登录您的微信，这可能会导致个人信息泄露的风险。我们选择平安的三者险，就是为了避免找到加价的保险贩子。因此，我们强烈建议您拒绝加价代抢行为。

## 使用说明

请按照以下步骤操作：

1. 确保您已安装Python 3.6或更高版本。
2. 打开`main.py`文件，修改带有`*`标记的参数。参数说明如下：
   - `contactName`：您的姓名
   - `contactTelephone`：您的手机号
   - `vehicleNo`：您的车牌号。车牌号格式应为：京A-12345 或 京B-12345。如果车牌号中包含字母，字母需要大写
   - `sessionId`和`signature`：这两个参数需要从微信小程序抓包得到。具体的抓包方法请自行百度搜索。
3. 运行`main.py`文件。如果提示1501，那么表示`sessionId`和`signature`参数设置正确。此时，您可以按回车键开始自动预约。

## 问题反馈

如果您在使用过程中遇到任何问题，欢迎在[Issues](https://github.com/yon1ng/beijing_pinan_motor/issues)中提出。我们会尽快回复并解决您的问题。