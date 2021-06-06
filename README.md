[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Release](https://img.shields.io/github/release/Pixisoft/PackageExporter.svg?logo=github)](https://github.com/Pixisoft/UnityPackageExporter/releases/latest)
[![Unity Engine](https://img.shields.io/badge/unity-2021.1.1f1-black.svg?style=flat&logo=unity&cacheSeconds=2592000)](https://unity3d.com/get-unity/download/archive)
[![CI](https://github.com/Pixisoft/PackageExporter/actions/workflows/build.yml/badge.svg)](https://github.com/Pixisoft/PackageExporter/actions/workflows/build.yml)

# Package Exporter

Export multiple packages by just one click, with no need to uncheck the assets.

<p align="center">
  <img src="./etc/package-manage.png"/>
</p>

## Features

* Export multiple packages in a project
* Export method similar to `.gitignore` (easy for coder)
* Lightweight, no other dependencies
* Clean, no files are generated
* Highly compatible to any Unity version

## :hammer: How to use?

### :mag: 1. Import Package

You will need to import the package to your project. The package 
can be download from [here](https://github.com/Pixisoft/PackageExporter/releases).

### :mag: 2. Start using Package Exporter Window

You can start the `PackageExporter` window from the menu bar `PackageExporter`.

### :mag: 3. Fill package info and generate `.unityignore` file

<img src="./etc/package-info.png"/>

After you fill the info, then hit `Generate Unity Ignore` button.

### :mag: 4. Edit `.unityignore` file

All the `.unityignore` files can be found under `PackageExporter/unityignore`
directory. 

### :mag: 5. Export...

Once the `.unityignore` file is generated, the according package 
export button should appear.

### :mag: 6. Enjoy!

Now you can manage as many packages you want to export! :tada:

## Unityignore Example

Generated `.unityignore` file for `Hello World` package.

```
# 
# Thank you for using `Package Exporter`. This is the generated 
# unityignore file.
# 
# Package Name: Hello World
# Version: 1.0.0
# Creation Date: 2017-10-25 06:58:14 
# 
# Package Link: https://github.com/Pixisoft/PackageExporter
# Author: Shen, Jen-Chieh
# Email: pixisoft.tw@gmail.com
# 

# Ignore this plugin itself.
ProjectExporter

```

## :rocket: Exporting

Export the package `Hello World`.

<p>
  <img src="./etc/export-package.gif"/>
</p>

## Todo List

- [ ] Support ingore extension syntax. (*.meta)

## License

Licensed under MIT. See [LICENSE.txt](https://github.com/Pixisoft/PackageExporter/blob/master/LICENSE.txt) for details.
