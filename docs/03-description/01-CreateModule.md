# Module Creator

## 機能
- アバターや衣装の一部のみを取り出し、他のアバターに使用することを目的とした機能
- 欲しいメッシュの箇所を指定した上でウェイトやPhysBone等を走査し必要最低限の構成のPrefab Variantを生成

## 実行場所
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニュー
- Module Creator / Create Module
- Module Creator / Create Module (Advanced)

## 使い方

### Create Module
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニューからModule Creator / Create Module
- 選択されたメッシュを含むPrefabとそのインスタンスがAssetsとHierarchyにそれぞれ生成されます
- 他のアバターに適用する際はMA SetupOutfits/Merge Armature/Bone Proxyを想定しています。

### Create Module (Advanced)
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニューからModule Creator / Create Module (Advanced)
- 複数のSkinned Mesh Rendererをまとめて処理ができます。
- Editボタンからメッシュの一部のみが選択できます。詳細は[Triangle Selector](../TriangleSelector)から
