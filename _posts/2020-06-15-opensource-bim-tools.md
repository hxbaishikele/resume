---
title: "开源建筑信息模型（BIM）工具列表"
lang: zh
ref: posts/2020-06-15-opensource-bim-tools
permalink: /posts/2020-06-15-opensource-bim-tools
excerpt: "本页面将持续收集和记录建筑信息模型（BIM）有关开源工具和资料"
date: 2020-06-15

category: posts
tags:
  - posts
  - opensource
  - bim
  - tool
  - software
  - digital twin
---


本页面主要收集和记录建筑信息模型（BIM）相关的开源工具和资料，欢迎提出建议或补充。

## IFC解析处理
1. [IfcOpenShell](http://ifcopenshell.org/): 在OpenCASCADE几何建模内核基础上构建的IFC解析工具包，在其上构建的IfcOpenShell-python为利用python处理BIM模型提供了很好的基础，支持Linux系统。工具包同时包括IfcMax、IfcBlender及BIMserver插件，分别为3ds Max、Blender和BIMserver提供IFC文件存取功能。此外，工具包的IfcConvert小工具也可将IFC快速转换为obj等常见三维模型格式。不足之处是仅支持STEP格式的IFC文件处理，尚不支持IFCXML等格式。有关源码在[GitHub](https://github.com/IfcOpenShell/)基于LGPL协议开放。
2. [XBim Toolkit](https://docs.xbim.net/):同样基于OpenCASCADE几何建模内核构建，包括Xbim Essentials、Xbim Geometry两个核心模块用于IFC存取和几何数据处理，支持STEP和IFCXML两种格式。还提供Xbim Xplorer、Xbim WebUI、Xbim Utilities、Xbim Exchange等模块，分别提供了WPF桌面端、网页端BIM模型查看、文件批处理、COBie数据交换等功能。目前所有代码都在[GitHub](https://github.com/xBimTeam)基于CDDL协议公开，但从其官网来看有商业化的计划。
3. [IFC++](https://ifcquery.com/)：基于C++构建的IFC解析工具包，支持并行数据解析，采用MIT协议开源，商业友好，源码也在[GitHub](https://github.com/ifcquery/ifcplusplus)开放。
4. [apstex IFC Framework](http://www.apstex.com/)：前身是Open IFC Tools，基于Java开发，支持IFC存取、几何数据处理、桌面端和网页端3D显示等，学术研究免费。
5. [IfcWebServer](https://ifcwebserver.org/)：或许是最老的网页端IFC工具之一，支持IFC存取、三维可视化、4D模拟、子模型提取以及IFC向Neo4j图数据库的转换等等，源码在[GitHub](https://github.com/ifcwebserver/ifcwebserver)开放。

## 3D造型
1. [FreeCAD](https://freecadweb.org/)：开源3D参数化建模工具，支持多操作系统，支持python二次开发，可利用前述IfcOpenShell模块实现IFC的存取，源码在[GitHub](https://github.com/FreeCAD/FreeCAD)以LGPL协议开放。
2. [BRL-CAD](http://brlcad.org/)：宣称100%开源免费，支持多操作系统，具备CSG和B-REP造型内核，美国军方长期将其作为武器系统建模工具。有关代码在[SourceForge](https://sourceforge.net/projects/brlcad/)开源。
3. [Blender](https://www.blender.org/)：开源的三维建模及动画制作软件，具备三维建模、关键帧及骨骼动画制作等功能，支持导入多种三维数据格式，具备python二次开发接口，同时可利用IfcOpenShell存取IFC模型数据，采用GPL协议开源。

## 3D可视化
1. [Three.js](https://threejs.org/):基于WebGL的 网页三维显示库，支持多种三维数据格式，目前常见的前端WebGL三维显示多在其基础上实现，如Autodesk Forge的前端三维显示，广联达BIMFace的前端三维显示等，在[GitHub](https://github.com/mrdoob/three.js/)以MIT协议开源。
2. [Cesium.js](https://cesium.com/cesiumjs/):基于javascript构建的前端三维GIS库，由AGI和Bentley共同发起，3DTiles规范的发起者，在[GitHub](https://github.com/CesiumGS/cesium)以Apache 2.0协议开源，商业友好。
3. [Helix Toolkit](http://helix-toolkit.org/)：基于.Net平台的3D数据处理和可视化模块，包括WPF和SharpDX（DirectX 3D的C#封装）两种三维显示模式，在[GitHub](https://github.com/helix-toolkit/helix-toolkit)以MIT协议开源，商业友好。

## BIM服务器
[BIMserver](http://bimserver.org/)：开源免费的BIM服务器平台，基于IFC存储BIM模型，支持版本管理、碰撞检测、可视化
模型校验、子模型合并提取等诸多功能，同时还提供了[BIMSurfer](https://github.com/opensourceBIM/BIMsurfer)作为网页端IFC浏览模块，在[GitHub](https://github.com/opensourceBIM/BIMserver)以AGPL协议开源。

自BIMserver开源以来，近10年间在其上发展和衍生了一系列的BIM工具，详见[opensourceBIM的GitHub主页](https://github.com/opensourceBIM)。

## BIM模型校验/审查
1. [IfcDoc](https://github.com/buildingSMART/IfcDoc)及其新一代版本[IfcXtreme](https://github.com/IfcXtreme/IfcXtreme)：buildingSMART官方发布的工具，支持IFC Schema定义、基于mvdXML的模型校验等等，采用MIT和GPL3协议开放。
2. [python-mvdxml](https://github.com/opensourceBIM/python-mvdxml)：opensourceBIM开源的mvdxml模型校验工具，基于IfcOpenShell实现。
3. [IfcValidator](https://github.com/opensourceBIM/IfcValidator)：基于BIMserver实现的IFC模型校验工具，同样由opensourceBIM开源。
4. 已停止更新的IFC校验工具：[JavaModelChecker](https://github.com/opensourceBIM/JavaModelChecker)和[mvdXMLChecker](https://github.com/opensourceBIM/mvdXMLChecker)。


如您发现新的开源BIM工具，欢迎将有关信息发送至lin611(AT)tsinghua.edu.cn(将`AT`替换为`@`)，请在邮件主题中注明“开源BIM”，我们将及时更新有关信息。