## VIVE CAMERA UTILIZE FOR EGOCENTRIC VIEW

![](docs/index.jpg)

### 何

だいたい一人称視点でぴったり見えている風、に VIVE のフロントカメラを描く。

### 環境

* Unity 2018.1.6f1（たぶん異なるバージョンでも問題無い）
* VIVE（無印）
* [SteamVR Unity Plugin v1.2.3](https://github.com/ValveSoftware/steamvr_unity_plugin/releases/tag/1.2.3)

### ビルド・実行

* このリポジトリを落としてくる
* [SteamVR Unity Plugin v1.2.3](https://github.com/ValveSoftware/steamvr_unity_plugin/releases/tag/1.2.3) を落としてくる
* `Assets/Scenes/SampleScene.unity` シーンを開く。**（絶対に `EgocentricView.unity` はひらかないこと！）**
* SteamVR Unity Plugin の .unitypackage を展開
* それから、`EgocentricView.unity` を開いて
* VIVE がつながっていることと、SteamVRの設定からカメラ利用を許可していることを確認（下図）してから
* 実行

![](docs/vivefrontcamera.png)

#### 注意点

先に SteamVR Unity Plugin を展開しないと、`EgocentricView.unity` シーンから見てアセットが全然無い状態になるので、シーンが壊れます。この場合は、**絶対に保存せずに**、SteamVR Unity Plugin の展開を済ませ、一度Unityを落として、再度`EgocentricView.unity`を開き直してください。