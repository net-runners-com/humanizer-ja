# humanizer-ja（統合版）

以下2つのMITライセンスOSSを統合・再構成した個人用スキル。

- [gonta223/humanizer-ja](https://github.com/gonta223/humanizer-ja) — 生成時回避型の設計と「消した後に何を入れるか」の指示を骨格に採用
- [makotofalcon/humanizer-ja](https://github.com/makotofalcon/humanizer-ja) — 3層構造とBefore/After検出パターンを統合

## 導入

- Claude Code: このフォルダを `~/.claude/skills/humanizer-ja/` に配置（シンボリックリンク可）
- Claude.ai: このフォルダをZIP化して カスタマイズ > スキル からアップロード

## 育て方

- `my-style.md` に自分の文章を貼る（文体を寄せる先）
- 拾い損ねたAI臭い表現は `my-ng-words.md` に追記
