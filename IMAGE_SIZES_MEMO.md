# EN-LIGHT個別指導スクール Website - Image Sizes Reference

## Image Size Requirements by Page

### 1. **index.html (トップページ)**
- **ヒーロー背景画像**: 全画面背景（background-size: cover）
  - `images/hero-background.jpg` - 個別指導塾の教室風景（1920×1080px）
- **EN-LIGHTの特長画像（3枚）**: 横長（width: 100%; height: 200px; object-fit: cover）
  - `images/feature-individual-guidance.jpg` - 完全個別指導（1200×800px）
  - `images/feature-achievements.jpg` - 豊富な実績（1200×800px）  
  - `images/feature-learning-joy.jpg` - 学習の楽しさを発見（1200×800px）

### 2. **concept.html (指導方針)** - 画像なし

### 3. **course.html (コース案内)** - 画像なし

### 4. **result.html (成績UP・合格実績)**
- **生徒の写真（3枚）**: 1:1正方形（width: 80px; height: 80px; border-radius: 50%）
  - `images/student-tanaka.jpg` - 田中太郎君の写真（400×400px）
  - `images/student-sato.jpg` - 佐藤花子さんの写真（400×400px）
  - `images/student-yamada.jpg` - 山田次郎君の写真（400×400px）

### 5. **room.html (教室紹介)**
- **教室ギャラリー画像（5枚）**: 横長（height: 300px; object-fit: cover）
  - `images/room/classroom-booth.jpg` - 個別指導ブース（1600×1200px）
  - `images/room/study-room.jpg` - 自習室（1600×1200px）
  - `images/room/meeting-room.jpg` - 面談室（1600×1200px）
  - `images/room/reception.jpg` - 受付・待合スペース（1600×1200px）
  - `images/room/library.jpg` - 資料コーナー（1600×1200px）

### 6. **teachers.html (講師紹介)**
- **講師写真（6枚）**: 1:1正方形（width: 120px〜150px; height: 120px〜150px; border-radius: 50%）
  - `images/teacher/principal.jpg` - 塾長 田中優一（600×600px）
  - `images/teacher/sato.jpg` - 佐藤美香先生（600×600px）
  - `images/teacher/yamada.jpg` - 山田健太先生（600×600px）
  - `images/teacher/suzuki.jpg` - 鈴木正明先生（600×600px）
  - `images/teacher/takahashi.jpg` - 高橋絵里先生（600×600px）
  - `images/teacher/kobayashi.jpg` - 小林大輔先生（600×600px）

### 7. **contact.html (お問い合わせ)** - 画像なし

## 推奨画像仕様

### サイズ別推奨解像度
- **ヒーロー背景画像**: 1920×1080px（16:9比率、Full HD対応）
- **横長（特長画像用）**: 1200×800px（3:2比率、Retina対応）
- **1:1正方形（大）**: 600×600px（講師写真用、高精細対応）
- **1:1正方形（小）**: 400×400px（生徒写真用、高精細対応）
- **教室画像**: 1600×1200px（4:3比率、高解像度対応）

### 技術仕様
- **ファイル形式**: JPG推奨（Web最適化済み）、WebP対応推奨
- **容量**: 
  - ヒーロー背景画像（1920×1080px）: 500KB〜800KB程度
  - 特長画像（1200×800px）: 200KB〜500KB程度
  - 講師写真（600×600px）: 150KB〜300KB程度
  - 生徒写真（400×400px）: 100KB〜200KB程度
  - 教室画像（1600×1200px）: 300KB〜600KB程度
- **レスポンシブ対応**: 全画像がスマホサイズまで自動調整
- **オブジェクトフィット**: `cover`設定で比率維持・トリミング
- **高解像度対応**: Retina/4Kディスプレイでも鮮明に表示

## ディレクトリ構造
```
images/
├── hero-background.jpg             # ヒーロー背景画像（1920×1080px）
├── feature-individual-guidance.jpg  # 完全個別指導（1200×800px）
├── feature-achievements.jpg         # 豊富な実績（1200×800px）
├── feature-learning-joy.jpg         # 学習の楽しさを発見（1200×800px）
├── student-tanaka.jpg              # 生徒写真（田中太郎君）（400×400px）
├── student-sato.jpg                # 生徒写真（佐藤花子さん）（400×400px）
├── student-yamada.jpg              # 生徒写真（山田次郎君）（400×400px）
├── room/
│   ├── classroom-booth.jpg         # 個別指導ブース（1600×1200px）
│   ├── study-room.jpg             # 自習室（1600×1200px）
│   ├── meeting-room.jpg           # 面談室（1600×1200px）
│   ├── reception.jpg              # 受付・待合スペース（1600×1200px）
│   └── library.jpg                # 資料コーナー（1600×1200px）
└── teacher/
    ├── principal.jpg               # 塾長 田中優一（600×600px）
    ├── sato.jpg                   # 佐藤美香先生（600×600px）
    ├── yamada.jpg                 # 山田健太先生（600×600px）
    ├── suzuki.jpg                 # 鈴木正明先生（600×600px）
    ├── takahashi.jpg              # 高橋絵里先生（600×600px）
    └── kobayashi.jpg              # 小林大輔先生（600×600px）
```

## 必要画像総数: 15枚

### 内訳
- **ヒーロー背景画像**: 1枚（1920×1080px 横長）
- **トップページ特長画像**: 3枚（1200×800px 横長）
- **生徒写真**: 3枚（400×400px 正方形）
- **教室ギャラリー画像**: 5枚（1600×1200px 横長）
- **講師写真**: 6枚（600×600px 正方形）

### 撮影時のポイント
- **ヒーロー背景画像**: 個別指導塾の教室全体、生徒と講師の学習風景、明るく希望に満ちた雰囲気
- **特長画像**: 個別指導の様子、成績向上のイメージ、楽しい学習風景など
- **生徒写真**: 笑顔で親しみやすい表情、制服または私服で撮影
- **教室ギャラリー**: 明るく清潔感のある教室内部、自然光での撮影推奨
- **講師写真**: プロフェッショナルな印象、明るく親しみやすい表情
- **カラーテーマ**: サイトのブランドカラー（#6AB6D9 水色系）に合う明るく清潔感のある色調

### 現在の画像利用状況と改善必要箇所
- **現在使用中の画像**: トップページの3つの特長すべてで同じ画像（1.png）を使用（要差別化）
- **プレースホルダー画像**: 
  - 教室ギャラリーは背景色のみ（実画像必要）
  - 講師写真は背景色のみ（実写真必要）
  - 生徒写真は実画像あり（`images/student1.jpg`, `images/student2.jpg`, `images/student3.jpg`）

### 高解像度対応により改善される点
- **ガビガビ防止**: 従来比2〜3倍の解像度で鮮明な表示
- **Retina対応**: 高精細ディスプレイでもクリアな画質
- **スケーラビリティ**: 将来的な高解像度対応にも柔軟に対応

**作成日**: 2025年7月6日  
**更新日**: 2025年7月6日