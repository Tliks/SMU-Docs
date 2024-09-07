# Module Creator

## 機能
- アバターや衣装の一部のみを取り出し、他のアバターに使用することを目的とした機能
- 欲しいメッシュの箇所を指定した上でウェイトやPhysBone等を走査し必要最低限の構成のPrefab Variantを生成

## 実行場所
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニュー
- Module Creator / Create Module
- Module Creator / Create Module (Merged)
- Module Creator / Create Module with Triangle Selector

## 使い方

### Create Module
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニューからModule Creator / Create Module
- 選択されたメッシュを含むPrefabとそのインスタンスがAssetsとHierarchyにそれぞれ生成されます
- 他のアバターに適用する際はMA SetupOutfits/Merge Armature/Bone Proxyを想定しています。

### Create Module (Merged)
- 複数のSkinned Mesh Rendererをまとめて単一のPrefabにします。それ以外は通常のCreate Moduleと同じです。
- 複数のSkinned Mesh Rendererがついたオブジェクトを選択した上で右クリックメニューからModule Creator / Create Module (Merged)

### Create Module with Triangle Selector
- 単一のSkinned Mesh Rendererのうち、その一部のみをPrefabにします。
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニューからModule Creator / Create Module with Triangle Selector
- Add SelectionからTriangle Selectorを起動
- 欲しい箇所のメッシュを指定した上でApply。詳細は[Triangle Selector](../TriangleSelector)から
- Create Moduleをクリック
- 未選択のモジュールを含むは選択していない箇所のPrefabも同時に出力します。メッシュを2つに分離するようなイメージです。
