# **创建域名**

 1、进入CDN客户控制台【域名列表】页面； 点击“添加域名”；           

![image.png](https://img1.jcloudcs.com/cms/b5b15af8-d4c9-4806-a050-e59c81ddbcf120180423142138.png)

2、 在打开的“新增加速域名”页面中填写或选择以下信息，然后点击“确定”按钮。

* 加速域名：填写需要对其内容做分发、加速的域名信息。

  请先完成域名在通信管理局的ICP备案后再做此项域名添加配置；

  域名填写字符只支持英文26个字母、10个阿拉伯数字以及横杠“-”'*'；

  支持泛域名，不支持泛域名与子域名以相同内容结尾的域名添加，如已经添加泛域名*.a.com,不支持在添加c.b.a.com或b.a.com；

  最多支持添加100个加速域名，如有更多的域名加速需求，请提交在线工单。

* 业务类型：请根据域名内容选择适当的业务类型。

  图片小文件：适用于静态网站、图片和小于10MB文件加速的场景；

  大文件下载：适用于大于20MB以上的大文件分发场景；

  视频文件：适用于音视频点播加速场景。

* 业务日常峰值带宽：请预估一下每日峰值带宽量，对于大文件下载和视频文件加速业务，也请您填写一下文件大小信息，便于我们合理为您调配资源。

* 回源方式：请根据实际需求选择IP回源、域名回源，或OSS回源，并对应填写源站IP地址、源站域名，选择OSS的bucket信息。京东云CDN支持多IP负载均衡回源，以及多IP、多域名备份回源，请您根据实际需要填写回源配置。

![image.png](https://github.com/jdcloudcom/cn/blob/cdn-new/image/CDN/%E8%87%AA%E5%AE%9A%E4%B9%89%E5%9B%9E%E6%BA%90host.png)
