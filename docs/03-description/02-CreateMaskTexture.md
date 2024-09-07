# Create Mask Texture

## 機能
- マテリアルや他ツール等で使用できるメッシュの任意の箇所のマスク画像等を生成する機能
- メッシュの箇所を指定した上で、選択箇所と非選択箇所に対してそれぞれ塗りつぶしや色の転送等を行ったテクスチャを生成

## 実行場所
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニューからSceneMeshUtils / Create Mask Texture

## 使い方
- Add SelectionからTriangle Selectorを起動
- メッシュの箇所を指定した上でApply。詳細は[Triangle Selector](../TriangleSelector)から
- 選択された箇所のメッシュがプレビューされます。
- 選択した箇所と選択されていない箇所をそれぞれどのような色にするか選択します。
    - white: 白に塗りつぶし
    - black: 黒に塗りつぶし
    - alpha: 透過に塗りつぶし
    - original: 元のテクスチャから転送
    - grayscale: 元のテクスチャから輝度情報のみ転送
- Create Mask Texture
- テクスチャがAssetsに保存されます
