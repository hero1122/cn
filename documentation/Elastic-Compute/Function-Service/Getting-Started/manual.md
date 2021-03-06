# 使用流程

本章简要介绍函数服务的使用流程。

使用简介：

公测期间，您如果想使用函数服务，请在产品详情页申请公测。

函数服务使用流程：

1. 创建函数：在线编写代码或上传代码包至函数服务，配置函数运行条件；
2. 测试函数：通过控制台测试函数代码或调用API触发函数执行，验证函数执行是否达到预期；
3. 发布函数版本和别名：为已测试验证的函数发布新版本，为此新版本配置云服务事件源触发函数，实现业务功能，新的函数功能迭代可在LATEST版本继续进行；
3. 函数监控：监控函数运行状态，通过配置报警策略，及时处理函数运行错误；
4. 函数日志：通过函数日志检查函数执行日志，排查函数运行错误。

 

## 创建函数

函数（Function）是调度与运行的基本单位，是一段代码的处理逻辑。您需要根据Function提供的函数接口形式编写代码，并将代码以函数的形式部署到函数服务。

函数创建详细信息请参阅[函数构建](../Operation-Guide/buildfunction/config-function.md)。

 
## 触发函数

函数由事件触发，函数服务目前支持OSS触发器和API网关触发器。

触发器详细信息请参阅[触发器](../Operation-Guide/invokefunction/triggermanagement/triggeroverview.md)。

此外，如不配置触发器，您也可以使用控制台、SDK等方式直接调用函数执行。

## 查看函数监控

通过云监控，用户可实时监控函数运行状况，保证业务平稳运行。

函数监控详细信息请参阅[函数监控](../Operation-Guide/monitor.md)。

## 查看执行日志

函数被执行后，您可以通过日志服务查询函数执行情况，Function将函数日志记录在日志服务中，您可以通过配置日志服务获取函数日志。

函数日志详细信息请参阅[函数日志](../Operation-Guide/function-log.md)。




