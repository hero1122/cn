# 版本管理

## 函数版本与别名

 
函数服务提供函数版本管理功能，便于用户管理开发、测试、生产环境中的函数代码，满足软件开发周期中的持续迭代。通过Function版本控制，您可以发布Function函数的一个或多个版本，以便在不同阶段或环境中使用Function函数的不同版本。
 
Function函数还支持为函数的版本创建别名，别名是指向特定Function函数版本的指针。利用别名，您可以回滚到Function函数之前任意版本。

 

## 管理版本

函数创建默认版本为LATEST版本，每个函数都有一个LATEST版本。函数代码稳定后可以进行发布操作，发布版本不允许进行修改。

建议：您可以使用测试稳定后发布的函数版本服务线上请求，并继续在LATEST版本上开发测试，保证业务的平稳运行。

### 发布版本

 1.用户登陆函数服务，进入“函数列表“页面。
 
 2.在“函数列表“中选择要配置的函数，单击函数名称进入该函数详情页。
 
 3.在函数详情页，选择LATEST版本，单击“操作”—“发布新版本”，弹出“发布新版本”窗口。
 
 4.在“发布新版本”界面，输入要发布函数版本的配置信息见表1。
 
 5.单击“发布”，完成版本创建。
 
 表1：函数版本配置信息表

| 配置信息 | 说明                                                       |
| -------- | ---------------------------------------------------------- |
| 描述     | 最大支持1000个英文字母、数字、空格、逗号、英文句号、中文。 |



 **说明：**

版本号由系统自动生成（使用日期时间作为版本号，例如：v20170819-190658）。

单个函数下最多可以发布10个版本。

函数需修改配置或代码后才能发布新版本。


### 删除版本

函数详情页面，选择函数版本，单击“操作”—“删除版本”，弹出“删除提示”，确认无误后单击“确定”，删除函数版本。

 

## 管理别名

别名指向特定的函数版本，可通过别名来调用该版本的函数。

### 创建别名

1.用户登陆函数服务，进入“函数列表“页面。

2.在“函数列表“中选择要配置的函数，单击函数名称进入该函数详情页。

3.在函数详情页，选择函数版本，单击“操作”—“创建别名”，弹出“创建别名”窗口。

4.在“创建别名”界面，输入要创建的函数别名的配置信息见表2，* 为必填项。

5.单击“确定”，完成别名创建。

表2 函数别名配置信息表

| 配置信息  | 说明                                                         |
| --------- | ------------------------------------------------------------ |
| * 别名名称 | 只能包含字母，数字、下划线和中划线；以字母/数字开头、结尾；长度不超过16个字符 |
| * 对应版本 |  从已有函数版本中关联函数版本                                 |
|  描述      | 最大支持1000个英文字母、数字、空格、逗号、英文句号、中文。   |




**说明：**

单个函数下最多可以创建10个别名。
 

### 删除别名

函数详情页面，选择函数别名，单击“操作”—“删除别名”，弹出“删除提示”，确认无误后单击“确定”，删除函数别名。
