# 生成AIを活用した業務効率化とトラブルシュート

## 発表内容の概要

### 目的
- 情報システム部門の日常業務で多い問い合わせやトラブルに対し、生成AIを使って効率的に解決する方法を紹介します。
- 初心者でも取り組みやすい基本例から、応用的な業務改善のヒントまで提示します。

---

## 構成

### 1. 基本編：日常トラブルの解決

#### ケース1：NECマルチライタ 8250Nの印刷トラブル
- **問い合わせ内容**:
  - 「NECマルチライタ 8250Nで印刷できない」
  - 「エラーランプが点滅。エラーコード 'E59' が表示される。」
- **生成AIを利用した解決プロセス**:
  1. **初回質問**: エラー内容と考えられる原因をAIに質問。
  2. **AIの回答**: 用紙サイズ設定の不一致が原因と推測。トレイ設定を確認するよう指示。
  3. **追加質問**: 用紙トレイを確認済みだが解決しない場合の他の原因を質問。
  4. **AIの回答**: センサー汚れ、ドライバーの更新不足を指摘。
  5. **解決策**: スプール設定を調整し、ドライバー更新後に正常印刷。
- **ポイント**:
  - 問題が具体化し、短時間で解決策を提示。

#### ケース2：社内システムのパスワードリセット
- **問い合わせ内容**:
  - 「パスワードを忘れた」「リセットリンクが届かない。」
- **生成AIの活用例**:
  1. **手順生成**: パスワードリセットの手順を簡潔に生成。
  2. **追加質問**: リセットメールが届かない場合の解決策。
  3. **解決策**: メールアドレス再確認、スパムフォルダの確認手順を案内。
- **ポイント**:
  - マニュアル作成や対応テンプレート生成に最適。

---

### 2. 応用編：生成AIによる業務改善例

#### ケース1：簡易スクリプトやバッチファイルの作成
- **例**:
  - ログを圧縮し、SFTPで送信するバッチファイルを生成。
- **AIの対応**:
  - 必要なスクリプトを即時生成し、ユーザー環境に合わせたコメントを付加。

#### ケース2：他部署からの問い合わせ対応
- **例**:
  - 営業部からの「英語マニュアルを要約し、日本語に翻訳してほしい」という依頼。
- **AIの対応**:
  - 要約文を生成し、その後日本語翻訳を提示。

---

### 3. 中～上級者向け：高度な生成AI活用例

#### ケース1：Outlookの受信メール解析＋RPA連携
- **例**:
  - 問い合わせメールをAIで解析し、要約と優先順位を付ける。
  - RPAツールでチケット発行を自動化。

#### ケース2：RAGを活用した情報検索
- **例**:
  - 社内掲示板ログやPDFマニュアルを検索対象に含め、特定トラブルの解決例をAIが要約。
- **ポイント**:
  - 古いデータ資産の再活用が可能。

---

## 生成AI活用のメリット

### 1. 問い合わせ対応の効率化
- 短時間で原因特定や解決策を提示。

### 2. 業務自動化
- バッチスクリプトやメール処理を自動化し、作業負担を軽減。

### 3. 情報の再活用
- 社内データ資産（掲示板やマニュアル）をAIで活用可能。

---

## 質疑応答
- 生成AIの他の応用例について、自由に質問してください！
