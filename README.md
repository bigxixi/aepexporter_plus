# AEP Exporter Plus
AEP流程中的AE动画导出脚本加强版。  
视频介绍：  
https://www.bilibili.com/video/BV1tP4y117cS/
  
  
[<img src="https://raw.githubusercontent.com/bigxixi/aepexporter_plus/main/readme%E9%85%8D%E5%9B%BE/UI-%E4%B8%BB%E7%95%8C%E9%9D%A2.png" width="50%" height="30%">](https://github.com/bigxixi/aepexporter_plus)  

原版脚本作者[@shrekshrek](https://github.com/shrekshrek),AEP动画具体规则和前端使用方法参见：  
https://github.com/shrekshrek/aep

## 下载和使用：   
下载 `aexporter_plus.jsx` 文件，[`在这里右键 - 链接另存为`](https://github.com/bigxixi/aepexporter_plus/releases/download/1.0.0/aexporter_plus.jsx).</br>
复制到 AE 的 Script 目录下，重启AE，这样就能从 AE 的 「文件」-「脚本」中看到它了。  

## 相比原版：    
1. 增加了图形界面，可选导出地址  
2. 优化图片导出速度  
3. 优化进度条显示精确度  
4. 智能检测父级图层是否忘了显示（否则导出动画会出错）  
5. 可选「不导出图片」，如果只修改了关键帧而未增减图层或者调整图层顺序、替换图层，勾选它可以跳过图层导出步骤，加快导出速度，方便在图层量巨大的项目中做简单修改。  
6. 可以导出个简单的HTML预览文件用以检验web端还原情况（预览需要跑一个本地服务）  
预览文件需要和导出的项目文件夹在同一个目录（有点绕，意思是最好保持默认导出的文件结构）  
默认是把THREE.js(r143)和AEP.js直接嵌入HTML文件中，可以点击最右边的小齿轮图标「⚙」修改为通过url引用。  

[<img src="https://raw.githubusercontent.com/bigxixi/aepexporter_plus/main/readme%E9%85%8D%E5%9B%BE/UI-%E5%BC%95%E7%94%A8%E6%96%B9%E5%BC%8F.png" width="50%" height="30%">](https://github.com/bigxixi/aepexporter_plus)  
[<img src="https://raw.githubusercontent.com/bigxixi/aepexporter_plus/main/readme%E9%85%8D%E5%9B%BE/UI-%E7%88%B6%E7%BA%A7%E6%8F%90%E7%A4%BA.png" width="50%" height="30%">](https://github.com/bigxixi/aepexporter_plus)  
[<img src="https://raw.githubusercontent.com/bigxixi/aepexporter_plus/main/readme%E9%85%8D%E5%9B%BE/UI-%E8%BF%9B%E5%BA%A6%E6%9D%A1.png" width="50%" height="30%">](https://github.com/bigxixi/aepexporter_plus)  
