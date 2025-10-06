### **demos/collision-detection/README.md**

````markdown
# 衝突判定デモ

高精度なポリゴン衝突判定システムのデモンストレーション

## 機能

- 🌟 複雑な形状のサポート（星形、六角形、三角形、十字、円）
- 📏 リアルタイムサイズ調整（10m〜60m）
- 🎯 ドラッグ&ドロップでの移動
- 💥 正確なポリゴン交差判定

## 使用技術

- **Ray Casting Algorithm**: 点のポリゴン内判定
- **Line Segment Intersection**: エッジ交差検出
- **Haversine Formula**: 地球上の距離計算

## 操作方法

1. 形状ボタンで図形の種類を選択
2. スライダーでサイズを調整
3. 青い図形をドラッグして移動
4. 赤い POI に近づくと衝突を検出

## コードの主要部分

```javascript
// ポリゴン衝突判定
function polygonsIntersect(poly1, poly2) {
  // Ray Casting + Edge Intersection
}

// 形状生成
function createShape(type, center, sizeInMeters) {
  // 各形状の頂点を計算
}
```
````
