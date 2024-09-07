# Remove Mesh From Scene

## 機能
- 非破壊でメッシュを削除する機能。
- 基本的にAAO Remove Meshと同じですが[Triangle Selector](../TriangleSelector)を用いることでシーン上から直接選択できるインターフェースの違いがあります。

## 実行場所
- Skinned Mesh RendererがついたオブジェクトにAdd ComponentからSceneMeshUtils / SMU Remove Mesh From Scene

## 使い方
- Add SelectionからTriangle Selectorを起動
- 消したい箇所のメッシュを指定した上でApply。詳細は[Triangle Selector](../TriangleSelector)から
- NDMF Previewが有効であれば削除されたメッシュがプレビューされます。
- NDMF準拠でビルド時にメッシュ削除
