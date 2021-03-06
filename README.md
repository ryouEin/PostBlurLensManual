# PostBlurLensマニュアル

## 導入〜加工までの流れ

1. EmoteSwitchを導入（[https://booth.pm/ja/items/1242826](https://booth.pm/ja/items/1242826)）
1. UnityにてアバターにPostBlurLensを導入
1. VRChatにてPostBlurLensを使用して写真を撮影
1. 撮影した写真をWEBアプリにて加工（[https://pbl.doll-profile.com/](https://pbl.doll-profile.com/)）

## Unityセットアップチュートリアル

<iframe width="560" height="315" src="https://www.youtube.com/embed/qfinLt_BCSo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## VRChat上での操作方法チュートリアル

<iframe width="560" height="315" src="https://www.youtube.com/embed/dD5k4y09XZw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## ワールド固定をしたい場合

カメラを入れたボーンに生成される `_PostBlurLens_Main` という名前のオブジェクトを固定してください。

（ろじらぼ様の[VRC_ObjectDropper](https://logilabo.booth.pm/items/1968729)が手軽に固定できてオススメです）

## PostBlurLensをアバターから消したい場合

アバターのルート、カメラを入れたボーン、及びヘッドボーン内にある `_PostBlurLens` から始まるオブジェクトを削除してください。
