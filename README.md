# GeoJson2UE (UE5 Content-Only Plugin)

## Introduction
Generates points, splines, and planes corresponding to real-world geographic information using geospatial GeoJson data within the UE5 engine.

## Supported Versions

- Unreal Engine 5.7

## Installation Methods (Two Options)

### Method A: Install to Project (Recommended for Beginners)

1. Download this repository (Code -> Download ZIP)

2. After extraction, place the `GeoJson2UE` folder into your project:

`YourProject/Plugins/GeoJson2UE`

3. Open your project and go to `Edit -> Plugins`

4. Search for your plugin name, enable it, and restart the editor.

### Method B: Install to Engine (Available to all projects)

Place `GeoJson2UE` in:

`UE_5.7/Engine/Plugins/GeoJson2UE`

**Note**

Please ensure the UE plugin "Cesium for Unreal" is enabled by default. 

Please enable the UE plugin "VaRest" by default.

Please enable the UE plugin "Geometry Script" by default.

If missing, you can install it in UE Fab.

## Usage

- Drag into the scene / Fill in the JSON / Run

- In the Content Browser, locate the Plugins/GeoJson2UE/JOSN_Ganerate folder. Drag the BP_UltimatePOI blueprint, BP_UltimateSpline blueprint, and BP_Ultimatesurface blueprint into the scene. Find the default group in the Details panel, fill in the Mesh JSON with GeoJson data containing point, line, and polygon data, and click the jsonArray button.

## License
This project uses the MIT License.


# GeoJson2UE（UE5 Content-Only Plugin）

## 簡介
使用地理GeoJson資料在UE5引擎中產生對應真實地理資訊的點、樣條線和平面

## 支援版本
- Unreal Engine 5.7

## 安裝方法（兩種方式）

### 方式A：安裝到專案（推薦新手）
1. 下載本倉庫（Code -> Download ZIP）
2. 解壓縮後把 `GeoJson2UE` 資料夾放到你的專案：
 `YourProject/Plugins/GeoJson2UE
3. 打開項目，進入 `Edit -> Plugins`
4. 搜尋你的插件名，勾選啟用，重啟編輯器

### 方式B：安裝到引擎（所有項目可用）
把 `GeoJson2UE` 放到：
`UE_5.7/Engine/Plugins/GeoJson2UE

**注意**
請預設開啟UE插件“Cesium for Unreal”
請預設開啟UE插件"VaRest"
請預設開啟UE插件"Geometry Script"
如缺失可在UE Fab自行安裝

## 使用方法
- 拖進場景 / 填寫json / 運行
- 在內容瀏覽器裡找到 Plugins/GeoJson2UE/JOSN_Ganerate資料夾，將其中的BP_UltimatePOI藍圖、BP_UltimateSpline藍圖和BP_Ultimatesurface藍圖拖入場景中，找到細節面板的預設分組，將含有點、線、面資料的GeoJson資料填入場景中，找到細節面板的預設為按鈕即可。


## 許可證
本項目使用 MIT License
