Angle
==========================

マウスでドラッグすることのできるノブ(Knob)を表示します。


![](https://dl.dropboxusercontent.com/u/153254465/screenshot2/ss%202015-02-17%2021.52.00.png)

### 引数

|変数|説明|
|---|---|
|min|最小値|
|max|最大値|

### 使い方

```
using UnityEngine;
using UnityEditor;

public class AngleExample : MonoBehaviour
{
    [Angle(0, 360)]
    public float angle;
}
```
