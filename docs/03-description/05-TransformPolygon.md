# Transform Polygon
info: 開発途中につきコンポーネントがありません。

## 機能
- メッシュの一部にのみTransformを適用する機能。
- 通常メッシュの移動、回転、スケールはウェイトに従って動作しますが、そのウェイトが意図した通りに配置されていない場合、任意の箇所にのみ効果を適用できません。
- この機能は非破壊でMeshを直接編集することで任意の頂点に対してのみ追加のTransformの値を加算します。

## 実行場所
- Skinned Mesh RendererがついたオブジェクトにAdd ComponentからSceneMeshUtils / SMU Transform Polygon

## 使い方
- Add SelectionからTriangle Selectorを起動
- 適用したい箇所のメッシュを指定した上でApply。詳細は[Triangle Selector](../TriangleSelector)から
- コンポーネント上にあるTransformに準拠した項目の数値を変更します
- NDMF Previewが有効であれば選択されたメッシュのみPosition等が変化します。
- NDMF準拠でビルド時にMeshを編集