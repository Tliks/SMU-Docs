# Create Module

## 機能
- アバターや衣装の一部のみを取り出し、他のアバターに使用することを目的とした機能
- 欲しいメッシュの箇所を指定した上でウェイトやPhysBone等を走査し必要最低限の構成のPrefab Variantを生成

## 実行場所
- Skinned Mesh Rendererがついたオブジェクトの右クリックメニューからSceneMeshUtils / Create Module

## 使い方
- Add/Edit Triangle SelectionからTriangle Selectorを起動
- 欲しい箇所のメッシュを指定した上でApply。詳細は[Triangle Selector](../TriangleSelector)から
- 選択された出力対象の箇所のメッシュがプレビューされます。
- Create ModuleもしくはCreate Both Module
- 基本的にそのままMAセットアップ可能なメッシュやArmature等を内包したPrefabとそのインスタンスがAssetsとHierarchyにそれぞれ生成されます
- Create Both Moduleは選択したメッシュと選択されていないメッシュでそれぞれPrefabを生成します。独立した合計2つのメッシュに分離するような機能です。
