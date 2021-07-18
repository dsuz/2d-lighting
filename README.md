Unity の URP を使った 2D Lighting で「先の見えない洞窟」を作ったサンプルです。

![](https://user-images.githubusercontent.com/4126881/126061924-14501145-b743-4aa7-9b38-4b5d0f056b98.gif)

機能としては ShadowCaster2D コンポーネントを使います。しかし設定が面倒なので今回は [ShadowCaster2DExtensions](https://forum.unity.com/threads/script-for-generating-shadowcaster2ds-for-tilemaps.906767/) を使いました。

地形のアセット（スプライト）には [Free 8-Bit Pixel Pack](https://assetstore.unity.com/packages/2d/environments/free-8-bit-pixel-pack-79530) を使い、[NormalMap-Online](https://cpetry.github.io/NormalMap-Online/) を使って Normal Map を自動生成しています。