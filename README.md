# Ascetic's Unity Prototype

[![npm](https://img.shields.io/npm/v/ascetic.unity.prototype?style=for-the-badge)](https://www.npmjs.com/package/ascetic.unity.prototype)
[![npm](https://img.shields.io/npm/dw/ascetic.unity.prototype?style=for-the-badge)](https://www.npmjs.com/package/ascetic.unity.prototype)
[![GitHub](https://img.shields.io/github/license/alexzayats/ascetic.unity.prototype?style=for-the-badge)](https://github.com/AlexZayats/ascetic.unity.prototype)
[![GitHub](https://img.shields.io/github/workflow/status/alexzayats/ascetic.unity.prototype/Node.js%20Package?style=for-the-badge)](https://github.com/AlexZayats/ascetic.unity.prototype)

Unity package for creating prototypes. Contains simple colored textures and materials for simple 3D objects.

## Installation

**Ascetic's Unity Prototype** is used through **Unity's Package Manager**. In order to use it you'll need to add the following lines to your `Packages/manifest.json` file. This has to be done so your Unity editor can connect to NPM's package registry.

```
"scopedRegistries": [
  {
    "name": "NPM",
    "url": "https://registry.npmjs.org",
    "scopes": [
      "ascetic"
    ]
  }
]
```

After that you'll be able to visually control what specific version of **Ascetic's Unity Prototype** you're using from the package manager window in Unity.

From Unity IDE: Window -> Package Manager
* Click "+" -> Add package from git URL
* Enter "ascetic.unity.prototype"
* Click "Add"

Enjoy!
