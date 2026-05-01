# Suzune-Platypus Skills

Claude用カスタムSkillのコレクションです。
実際のWebアプリ開発プロジェクトの体験をベースに作成しました。

---

## Skill一覧

### / ClaudeAI

| Skill | 内容 |
|-------|------|
| [webapp-design](./ClaudeAI/webapp-design/) | WebアプリをAIと一緒に設計るSkill |
| [webapp-design-diagnostic](./ClaudeAI/webapp-design-diagnostic/) | Webアプリ設計スキルを診断するSkill |

---

## 各フォルダの構成

skill-name/ 　　  
  　├─ skill-name.skill ← インストール用ファイル（ダウンロードして使う）　　  
  　└─ files　  
  　  　  　├─ SKILL.md ← Skillの定義ファイル（中身を確認できます）　　  
  　  　  　└─ references/ ← SKILL.mdが参照するサブファイル群　  　


> `.skill`ファイルと`files`フォルダ内のファイルは同一の内容です。
> 中身を確認してからインストールしたい方はSKILL.mdをご覧ください。

---

## Skillの登録方法

> PCブラウザ（claude.ai）での操作を推奨します。

1. 使いたいSkillの `.skill` ファイルをダウンロード
2. claude.ai のチャットに `.skill` ファイルをドラッグ＆ドロップ
3. claude.ai にインストールを依頼
4. インストール完了後、チャットで起動フレーズを入力して使用開始

各Skillの起動フレーズは、各フォルダのREADMEを参照してください。

---
## ライセンス
MIT License

## 免責事項
本Skillの出力結果の正確性・完全性を保証するものではありません。
利用により生じたいかなる損害についても作者は責任を負いません。

---

*作成者: SUZUNE / Suzune-Platypus*
