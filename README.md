## 個人開発まとめ（Portfolio Repository）

ここでは、これまで個人・複数人で開発・研究してきた成果物を一覧でまとめています。  

## ハッカソン

### LLM人狼ゲーム（AI-Werewolf）

geek-camp 2025/開発人数:3人

https://github.com/arkyork/ai-werewolf

LLM（大規模言語モデル）に 襲撃対象の選定から台詞生成まで を一任し、人間プレイヤーが推理に集中できる人狼ゲームです。


#### 私の担当領域
- バックエンド全般
https://github.com/arkyork/ai-werewolf/tree/main/backend

#### 利用した技術
- Python
- Transformers
- PyTorch
- vLLM
- Docker
- Flask

#### 工夫点

* ローカル LLM を採用し、API コストを気にせず遊べる環境を実現
* 複数人開発のため Docker を用いて環境構築を自動化し、チーム全体での動作統一を確保
* Transformers での推論が遅かったため、vLLM を導入して推論速度を大幅に改善
* Unity（C#）フロント側との連携を考慮し、API の動作確認用テストケースを整備
* ロールを追加しやすい設計にするため、役職ごとにクラスを分けて実装

## 個人開発

## 学習


