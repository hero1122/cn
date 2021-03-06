# 价格总览

京东云对象存储以天为计费周期，每天固定时间进行前一天的账单结算，计费周期内的相关收费标准如下所示：

## 对象存储价格概览

<table>
 <tr>
  <td colspan="2">计费项</td>
  <td>标准型存储单价</td>
  <td>低冗余型存储单价</td>
 </tr>
 <tr>
  <td rowspan="2">存储容量</td>
  <td>实际存储空间占用量</td>
  <td>0.00427元/GB/天<br>（0.128元/GB/月）</td>
  <td>0.00233元/GB/天<br>（0.07元/GB/月）</td>
 </tr>
 <tr>
  <td>数据取回量</td>
  <td>-</td>
  <td>暂时免费</td>
 </tr>
 <tr>
  <td rowspan="6">访问流量</td>
  <td>内网流入流量</td>
  <td>免费</td>
  <td>免费</td>
 </tr>
 <tr>
  <td>内网流出流量</td>
  <td>免费</td>
  <td>免费</td>
 </tr>
 <tr>
  <td>外网流入流量</td>
  <td>免费</td>
  <td>免费</td>
 </tr>
 <tr>
  <td>外网流出流量</td>
  <td>0.50元/GB</td>
  <td>0.50元/GB</td>
 </tr>
 <tr>
  <td>CDN回源流出流量</td>
  <td>0.14元/GB</td>
  <td>0.14元/GB</td>
 </tr>
 <tr>
  <td>跨区域复制流量</td>
  <td>暂时免费</td>
  <td>暂时免费</td>
 </tr>
 <tr>
  <td rowspan="2">请求次数</td>
  <td>GET请求</td>
  <td>暂时免费</td>
  <td>暂时免费</td>
 </tr>
 <tr>
  <td>PUT请求</td>
  <td>暂时免费</td>
  <td>暂时免费</td>
 </tr>
</table>

## 云端数据处理价格概览

<table>
 <tr>
  <td colspan="3">计费项</td>
  <td rowspan="2" align="center">单价</td>
 </tr>
 <tr>
  <td rowspan="6">视频转码</td>
  <td>编码方式</td>
  <td>输出规格</td>  
 </tr>
 <tr>
  <td rowspan="5">视频H.264</td>
  <td>4K（3840×2160）及以下（即将上线）</td>
  <td>0.2800 元/分钟</td>
 </tr>
 <tr>
  <td>2K（2560×1440）及以下</td>
  <td>0.1400 元/分钟</td>
 </tr>
 <tr>
  <td>FHD（1920×1080）及以下</td>
  <td>0.0650 元/分钟</td>
 </tr>
 <tr>
  <td>HD（1280×720）及以下</td>
  <td>0.0330 元/分钟</td>
 <tr>
  <td>SD（640×480）及以下</td>
  <td>0.0220 元/分钟</td>
 </tr>
 <tr>
  <td colspan="3">视频截图</td>
  <td>0.1 元/千张</td>
 </tr>
<table>

说明：

- 转码费用 = 输出文件时长 x 转码单价
- 输出规格判定：按输出视频分辨率的长边和短边属于输出规格划定的范围进行判定，方式如下：以输出  HD (1280 x 720)及以下 规格为例，输出视频的分辨率长边不大于1280且短边不大于720则属于该输出规格。如输出视频的长边大于1280或输出视频的短边大于720，该输出视频属于更高输出规格。
- 若转码失败，失败时长不计入计费。
