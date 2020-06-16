---
title: "Opensource Tools for Building Information Modeling"
lang: en
ref: posts/2020-06-15-opensource-bim-tools
permalink: /en/posts/2020-06-15-opensource-bim-tools
excerpt: "This page collects and lists all available opensource tools for BIM"
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


In this post, we collect and list all available opensource tools for building information modeling, any comments and suggestions are welcome.

## Open & Save IFC
1. [IfcOpenShell](http://ifcopenshell.org/): an opensource IFC tool based on OpenCASCADE, supports both Linux and Windows, and provides IfcOpenShell-python for python developers. Meanwhile, IfcMax, IfcBlender and plugin for BIMserver are provided for 3ds Max, Blender and BIMserver. In addition, a tool called IfcConvert is also developed to convert IFC to various 3D formats. Currently, only IFC-SPF is supported, and support for IFCXML is still under development. Source code is available on [GitHub](https://github.com/IfcOpenShell/) under LGPL.
2. [XBim Toolkit](https://docs.xbim.net/): built based on OpenCASCADE, which provides Xbim Essentials, Xbim Geometry for loading/saving IFC and processing of geometric data, both IFC-SPF and IFCXML are supported. Moreover, Xbim Xplorer, Xbim WebUI, Xbim Utilities, Xbim Exchange are also included for development of WPF applications and 3D website, batch processing of files and data exchange based COBie respectively. Source code is available on [GitHub](https://github.com/xBimTeam) under CDDL.
3. [IFC++](https://ifcquery.com/): IFC loading and saving tool based on C++, supports parallel processing of IFC, source code is available on [GitHub](https://github.com/ifcquery/ifcplusplus) under MIT license。
4. [apstex IFC Framework](http://www.apstex.com/): a Java-based IFC tool, former version of it is also called Open IFC Tools, features including IFC loading/saving, geometry processing, 3D visualization are provided. The tool is free for research.
5. [IfcWebServer](https://ifcwebserver.org/): perhaps one of the oldest web-based IFC tools, supports IFC loading/saving, 3D/4D visualization, sub-model filtering and IFC to neo4j conversion. Source code is available on [GitHub](https://github.com/ifcwebserver/ifcwebserver).

## 3D Modeling
1. [FreeCAD](https://freecadweb.org/): opensouce 3D parametric modeling tool, support multiple operation systems, and built-in python API is available. FreeCAD could load and save IFC based IfcOpenShell-python, and source code is available on [GitHub](https://github.com/FreeCAD/FreeCAD) under LGPL.
2. [BRL-CAD](http://brlcad.org/): 100% free and opensource, support multiple operation systems, and provide hybrid CSG and B-REP geometry kernel. BRL-CAD is trusted by the U.S. military for modeling weapon systems. Source code is available on [SourceForge](https://sourceforge.net/projects/brlcad/).
3. [Blender](https://www.blender.org/):  opensource tool for 3D modeling and animation, support multiple 3D formats, and provide built-in python API, which could be used to load and save IFC files based on IfcOpenShell-python. Source code is opened on its website under GPL.
4. [OpenSCAD](http://www.openscad.org/): a programmer 3D solid modeling tool, supports multiple operation systems. OpenSCAD provides built-in modeling scripts and automatically compiles the scripts to generate 3D models. Source code is available on [GitHub](https://github.com/openscad/openscad/) under GPL v2.

## 3D Processing & Visualization
1. [Three.js](https://threejs.org/): a javascript library for WebGL-based 3D visualization, support multiple 3D formats, and perhaps is the most popular web 3D tool. Quite a few web 3D tools are built on top of threejs, for example, Autodesk Forge and Glodon BIMFace. Source code is available on [GitHub](https://github.com/mrdoob/three.js/) under MIT license.
2. [Cesium.js](https://cesium.com/cesiumjs/): a javascript library for 3D GIS, which comes from AGI and Bentley. Built-in support of 3DTiles is provided for visualization of large scale data set. Source code is available on [GitHub](https://github.com/CesiumGS/cesium) under Apache 2.0 license.
3. [Helix Toolkit](http://helix-toolkit.org/): a 3D visualization component based on .Net framework, source code is available on [GitHub](https://github.com/helix-toolkit/helix-toolkit) under MIT license.
4. [Trimesh](https://trimsh.org): a python library for 3D processing and visualization, support multiple 3D formats, and quite a few functions including convex hull, boolean operation, voxelization, etc., are provided. Source code is available on [GitHub](https://github.com/mikedh/trimesh) under license. Our group also contributed an algorithm for solid voxelization, related paper could be found [here]({{ site.baseurl }}/en/publications/2018-11-24-automatic-space-detection-for-maintenance).

## BIM Server
[BIMserver](http://bimserver.org/)：opensource BIM server, support management, versioning, checking, filtering, integration, clash detection and visualization of IFC models,  and built-in support of WebGL-based Visualization BY [BIMSurfer](https://github.com/opensourceBIM/BIMsurfer). Source code is available on [GitHub](https://github.com/opensourceBIM/BIMserver) under AGPL.

Since BIMserver was born, many tools have emerged on top it, check [GitHub page of opensourceBIM](https://github.com/opensourceBIM) for detail.

## Model Checking & Validation
1. [IfcDoc](https://github.com/buildingSMART/IfcDoc) and its next generation called [IfcXtreme](https://github.com/IfcXtreme/IfcXtreme): which are provided by buildingSMART, support definition of IFC schema, model validation based mvdXML, source code is opened under MIT and GPL3 license.
2. [python-mvdxml](https://github.com/opensourceBIM/python-mvdxml): a mvdXML-based model validation tool opened by opensourceBIM, built on top of IfcOpenShell.
3. [IfcValidator](https://github.com/opensourceBIM/IfcValidator): a model validation tool for BIMserver, also opened by opensourceBIM.
4. tools not maintained anymore: [JavaModelChecker](https://github.com/opensourceBIM/JavaModelChecker) and [mvdXMLChecker](https://github.com/opensourceBIM/mvdXMLChecker)。


If you found new opensource tools not listed above, please do not hesitate to send the information to me: lin611(AT)tsinghua.edu.cn(replace`AT`with`@`), thank you very much.