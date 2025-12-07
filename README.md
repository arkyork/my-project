## 開発まとめ（Portfolio Repository）

ここでは、これまで個人・複数人で開発・研究してきた成果物を一覧でまとめています。  

## ハッカソン

### LLM人狼ゲーム（AI-Werewolf）

geek-camp 2025/開発人数:3人

https://github.com/arkyork/ai-werewolf

LLMに 襲撃対象の選定から台詞生成まで を一任し、人間プレイヤーが推理に集中できる人狼ゲームです。


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

### 重ね文字
Pythonで「重ね文字」を実装したレポジトリとなっています。

https://github.com/arkyork/stackglyph

### 七並べ
Pythonで「七並べ」を実装したレポジトリとなっています。 本リポジトリでは、ランダムエージェントと強化学習エージェント（PPO）によるプレイを実現しました。

https://github.com/arkyork/shichinarabe

## 学習

- LangChainの学習
RagAgentの作成や類似度検索の実装を通じてLangChainの基礎を学習
https://github.com/arkyork/langchain-learn

- LangGraphの学習
グラフ構造を用いた知識表現と推論の基礎を学習
https://github.com/arkyork/LangGraph-learn

- decoder-onlyモデルの実装
Transformerアーキテクチャに基づくdecoder-onlyモデルをPytorchで実装し、自然言語生成の基礎を学習
https://github.com/arkyork/llm-decoder

- 遺伝的アルゴリズム
https://github.com/arkyork/genetic-algorithm

- グラフの実装
https://github.com/arkyork/graph

