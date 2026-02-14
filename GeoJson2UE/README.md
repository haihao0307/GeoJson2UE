# GeoJson2UE（UE5 Content-Only Plugin）

## 简介
使用地理GeoJson数据在UE5引擎中生成对应真实地理信息的点、样条线和平面

## 支持版本
- Unreal Engine 5.7

## 安装方法（两种方式）

### 方式A：安装到项目（推荐新手）
1. 下载本仓库（Code -> Download ZIP）
2. 解压后把 `GeoJson2UE` 文件夹放到你的项目：
   `YourProject/Plugins/GeoJson2UE
3. 打开项目，进入 `Edit -> Plugins`
4. 搜索你的插件名，勾选启用，重启编辑器

### 方式B：安装到引擎（所有项目可用）
把 `GeoJson2UE` 放到：
`UE_5.7/Engine/Plugins/GeoJson2UE

注意：
请默认开启UE插件“Cesium for Unreal”
请默认开启UE插件"VaRest"
请默认开启UE插件"Geometry Script"
如缺失可在UE Fab自行安装

## 使用方法
- 拖进场景 / 填写json / 运行
- 在内容浏览器里找到 Plugins/GeoJson2UE/JOSN_Ganerate文件夹，将其中的BP_UltimatePOI蓝图、BP_UltimateSpline蓝图和BP_Ultimatesurface蓝图拖入场景中，找到细节面板的默认分组，将含有点、线、面数据的GeoJson数据填入Mesh Json，点击jsonArray按钮即可。


## 许可证
本项目使用 MIT License
