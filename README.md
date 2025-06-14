# Bリーグクラブ データ分析用 Power BI レポート
このリポジトリでは、YouTube チャンネル【DX塾】の「Power BI 実演ライブ」で使用する、Bリーグクラブに関するデータセットおよび Power BI レポートファイルを提供しています。  

**[Power BI 実演ライブ](https://powerbi-live.connpass.com/)**

ぜひご自身のPCにダウンロードして、一緒にPower BI Desktopを操作しながらライブをご覧ください。より一層学習効果が高まります。

---
## 📁 ディレクトリ構成
bleague_club/  
├─ dataset/   
│　　└─ bleague_club_total_20**.xlsx  
└─ bleague_club_day*.pbix  

---
## 🔧 セットアップ手順

### 1. データセットの配置

1. データセットとPower BI レポートをローカルPCにダウンロードしてください。
2. データセットは、以下のパス構成に従ってローカルPCに保存してください：
`D:\temp\bleague_club\dataset\bleague_club_total_20xx.xlsx`

このように保存することで、Power BI レポートが自動的にデータを読み込むようになります。

---
### 2. Dドライブが存在しない場合
Dドライブがない、または別の場所に保存したい場合は、以下の手順で Power BI のデータソースパスを変更してください：

1. このリポジトリの `dataset` フォルダーを任意のローカルフォルダーに保存してください。  
例：`C:\Users\YourName\Documents\bleague_club\dataset\bleague_club_total_2016.xlsx`　　
2. Power BI Desktop で `bleague_club_report.pbix` を開く  
3. メニューから「**変換データ**」をクリックして Power Query エディタを開く  
4. 各クエリの「**ソース**」ステップを選択  
5. ファイルパスを先ほど保存した場所に合わせて修正してください。

---

## ❓ サポート
データの読み込みやパスの変更に関して不明点がある場合は、  
YouTube チャンネル【DX塾】の「Power BI 実演ライブ」のコメント欄などで、お問い合わせください。  
可能な範囲でサポートいたします。
