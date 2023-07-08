# KOEWayfind FYP Project

Augmented Reality (AR) based navigation system for Kulliyyah of Engineering, IIUM. For final year project (FYP) 2022/2023.


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/KOE-Wayfind/.github/assets/60868965/463757e8-1277-4950-9fcb-f0d96e54e0ce">
  <img alt="KOE Wayfinder thumbnail" src="https://github.com/KOE-Wayfind/.github/assets/60868965/71744825-cb14-4a83-9147-0885bed8e14d">
</picture>

## Introduction

The project, titled "**Development of Turn-by-Turn Navigation in Kulliyyah of Engineering Using Natural Landmark Detection**", aims to address the challenges of indoor navigation within the Kulliyyah of Engineering building. Traditional GPS signals are ineffective indoors, and the absence of clear landmarks makes it difficult for users to navigate and orient themselves. To overcome these limitations, the project proposes the integration of Augmented Reality (AR) technology and natural landmark detection techniques.

By leveraging AR technology, users will receive real-time visual cues and information to enhance their navigation experience within the building. The project focuses on developing a turn-by-turn navigation system that utilizes natural landmark detection to identify distinctive features within the environment.

The primary objectives of the project include developing a marker-less localization technique using natural landmarks, building a turn-by-turn navigation system using AR, and providing an accessible solution for efficient indoor navigation within the Kulliyyah of Engineering building.

## Repositories

### Main Repositories

* [KOE-Wayfinder-App](https://github.com/KOE-Wayfind/KOE-Wayfinder-App) - AR Navigation App made using Unity3D
* [AR-server](https://github.com/KOE-Wayfind/AR-server) - Flask Python server to run the localization process
* [Hierarchical-Localization](https://github.com/KOE-Wayfind/Hierarchical-Localization) - Modified libraries so that it can run on GitHub codespace machines and return the desired result. AR-server is using this library.

### Data Collection

* [HLOC](https://github.com/KOE-Wayfind/HLOC) - Used for data collection and study of the performance of the localization process using Hierarchical Localization Pipeline.

### Database/Dataset

* [koe-floor-plans](https://github.com/KOE-Wayfind/koe-floor-plans) - Kuliyyah of Engineering 2D floor plans for all levels and all building according to scale.
* [koe-revit](https://github.com/KOE-Wayfind/koe-revit) - Floor plan that have been transform to 3D. This 3D model is used in Unity to bake the Navigation Mesh and provider AR occlusion.

## Software/tool used

- [Unity 3D](https://unity.com/) (Version 2021.3)
- Unity's [AR Foundation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@4.2/manual/index.html) package (Version 4.2)
- [Jetbrains Rider](https://www.jetbrains.com/rider/)
- [Autodesk Revit](https://asean.autodesk.com/products/revit/overview)
- [GitHub Codespaces](https://github.com/features/codespaces)

## Results

See video demonstration: https://youtu.be/rnIUBIEBne0
