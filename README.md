# Installation

### Using OpenUPM (For Unity 2018.3 or later)

This package is available on [OpenUPM](https://openupm.com).  
You can install it via [openupm-cli](https://github.com/openupm/openupm-cli).

```
openupm add com.unitypackage.uni-paste-board
```

### Using Unity Package Manager (For Unity 2018.3 or later)

Find the manifest.json file in the Packages folder of your project and edit it to look like this:

open Packages/manifest.json

```
{
  "dependencies": {
    "com.unitypackage.uni-paste-board":"https://github.com/UnityPackage/uni-paste-board.git",
    ...
  },
}
```


# Quick start
```csharp

// 获取剪切板内容
string value = UniPasteBoard.GetClipBoardString(); 

// 复制内容到剪切板
UniPasteBoard.SetClipBoardString(value); 

```


# link
- [Unity Custom Packages](https://docs.unity3d.com/Manual/CustomPackages.html)


