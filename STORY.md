# Day018 Story — Daily Routine Slotter

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day018専用にテーマをseed固定して再生成時の見た目を安定化
- health用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: routine_slots
- Mechanic: slot_assignment_with_streak
- Input/Output: task_cards -> checklist_timeline
- Audience Promise: higher_habit_streak
- Publish Hook: 連続達成を見ながら習慣を回す
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day018｜Daily Routine Slotter
習慣タスクを時間枠で回しやすくするルーティンプランナー。（話題:HN Frontpage）
