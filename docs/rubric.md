# Transdisciplinary Engineering 評価指標（ルーブリック）

[定義・構成要素フレームワーク](../docs/01_definition_and_framework.md)（A. Goal / B. Collaboration / C. Integration / D. 適用領域）に基づき、収集した論文を評価するための指標を以下に定義する。各論文はTitle/Abstract/Keywords（PDF入手可の場合は本文も参照）から判定する。

## 評価方針

- 3つの中核指標（Goal / Collaboration / Integration）は **1〜5点の順序尺度** で評価し、その論文が「どれだけTEらしいか（transdisciplinarityの実践度）」を測る。
- 2つの補助指標（方法論的貢献・実証水準）は研究としての **成熟度・質** を測る。
- 適用領域はカテゴリ変数として付与し、マッピング時の色分け等に用いる。
- 合議的な単一の「正解スコア」ではなく、Lattanzio et al. (2021) の "landscape" 概念に倣い、**多次元の位置づけ（マップ）** として結果を提示する。

## 中核指標（TEらしさ）

### G. Goal Orientation（目標特性）— 1〜5点
問題設定が ill-defined／wicked problem であり、社会的関連性を明示しているか。

| 点数 | 基準 |
|---|---|
| 1 | 単一分野内の明確に構造化された技術的問題（社会的関連性の言及なし） |
| 2 | 技術的問題が中心だが、応用先や社会的背景に軽く言及 |
| 3 | 産業・社会的課題を背景として明示し、部分的にill-definedな問題を扱う |
| 4 | 複数のステークホルダーに関わる社会的・産業的に重要な課題を明確に定義 |
| 5 | 明示的にwicked/ill-defined problemとして定義し、社会・環境・経済への影響を核心に据える |

### C. Collaboration Breadth（協働特性）— 1〜5点
分野横断の幅とステークホルダーの多様性。

| 点数 | 基準 |
|---|---|
| 1 | 単一の工学専門分野内での研究 |
| 2 | 工学内の複数専門分野（例：機械×電気）の連携 |
| 3 | 工学と隣接分野（情報科学、管理工学等）の連携 |
| 4 | 工学と社会科学・人文科学（経営学、心理学、政策科学等）の連携、または産学連携を明示 |
| 5 | 学術・産業・行政・市民/エンドユーザーなど多様なステークホルダーの共創プロセスを含む |

### I. Integration Depth（統合特性）— 1〜5点
知識・方法論・プロセスの統合の深さ。

| 点数 | 基準 |
|---|---|
| 1 | 各分野の知見を並置するのみ（統合なし） |
| 2 | 分野間の情報参照・比較はあるが、方法論の統合はない |
| 3 | 特定の方法論・ツールを分野横断的に適用（例：mixed methodsの部分的採用） |
| 4 | 複数分野の方法論・データ・プロセスを体系的に統合するフレームワークを提案 |
| 5 | 存在論・認識論を超えた真の知識統合（学術知×実践知の共創）を達成・実証 |

**TE-Index（複合指標）** = (G + C + I) / 3 （0.5刻み、最大5点）。TEの中核概念にどれだけ合致しているかの総合スコア。

## 補助指標（研究の成熟度）

### M. Methodological Contribution（方法論的貢献）— 1〜5点
| 点数 | 基準 |
|---|---|
| 1 | 既存手法のレビュー・解説のみ |
| 2 | 既存手法の小規模な改良・適用 |
| 3 | 新しい適用事例・ケーススタディの提示 |
| 4 | 新しいフレームワーク／手法／ツールの提案 |
| 5 | 新しいフレームワークの提案かつ他分野・他ケースへの一般化可能性を議論 |

### V. Validation Level（実証水準）— 1〜5点
| 点数 | 基準 |
|---|---|
| 1 | 概念的議論のみ（検証なし） |
| 2 | 簡易な例示（illustrative example） |
| 3 | 単一ケーススタディによる検証 |
| 4 | 複数ケース／実データによる検証 |
| 5 | 産業実装・長期運用や定量的効果測定を伴う実証 |

## 追加指標：分野横断度（Author / Method / Objective）— Add-on

既存のCollaboration Breadth（C）は「協働の広さ」を1つの順序尺度で捉えるが、**誰が(Author)・どんな方法で(Method)・何を目指して(Objective)分野を跨いでいるか**をそれぞれ独立に可視化するための追加指標。既存のG/C/I/M/Vとは独立に付与し、既存フィールドは変更しない。

### 分野taxonomy（8分類）

論文のAuthor / Method / Objectiveそれぞれについて、該当する分野を以下の8分類から**複数選択（multi-label）**で付与する。

1. Engineering（工学：機械・電気・土木・航空宇宙・産業工学等）
2. Natural Science（自然科学：物理・化学・生物・材料科学等）
3. Social Science（社会科学：社会学・経済学・政策科学・人類学等）
4. Management / Business（経営学・組織論・マーケティング等）
5. Data Science / CS（情報科学・計算機科学・統計・AI等）
6. Humanities（人文学：哲学・心理学・デザイン理論・倫理等）
7. Medicine / Health（医学・公衆衛生・看護等）
8. Other（上記に当てはまらない分野）

### 評価軸

- **Author disciplines**：著者の所属・専門性から読み取れる分野（著者リストの所属学部、共著構成、論文の記述スタイルから判断）。
- **Method disciplines**：採用されている方法論・手法・ツールが由来する分野（例：エスノグラフィー→Social Science、有限要素解析→Engineering、機械学習→Data Science）。
- **Objective disciplines**：研究の目的・問題設定が属する分野（例：製造効率の改善→Engineering、ユーザー行動の理解→Social Science、材料特性の解明→Natural Science）。

各軸について、該当する分野をリストアップし、その **分野数（span）** を算出する。

| span値 | 意味 |
|---|---|
| 1 | 単一分野（disciplinary） |
| 2 | 2分野にまたがる（inter-disciplinary的） |
| 3以上 | 3分野以上にまたがる（trans-disciplinary的な広がり） |

**Disciplinary Span Index (DSI)** = (author_span + method_span + objective_span) / 3 。Author・Method・Objectiveの3軸を通じてどれだけ分野を横断しているかを示す総合指標（既存のTE-Indexとは独立の補助指標として併記する）。

## カテゴリ変数（マッピング用メタデータ）

- **Domain（適用領域）**：Research / Practice / Education / Multiple（Wognum et al. 2019の3領域）
- **Application Theme（応用テーマ）**：例）Industry 4.0, Sustainability/Resilience, Social Innovation, Product Lifecycle/PLM, Systems Engineering, Design Methodology, Education, Digital Twin, Other
- **Disciplinary Pairing（統合分野の組み合わせ）**：例）Engineering×Engineering, Engineering×Social Science, Engineering×Management, Engineering×Data Science 等

## 評価シートのフィールド定義（papers/metadata の各レコード）

| フィールド | 説明 |
|---|---|
| id | 論文ID（連番） |
| title | タイトル |
| authors | 著者 |
| year | 出版年 |
| venue | 掲載媒体（会議 or ジャーナル） |
| keywords | キーワード |
| abstract | 要旨 |
| pdf_status | full_text / abstract_only |
| pdf_path | PDFファイルパス（入手時） |
| G, C, I, TE_index | 中核指標スコア |
| M, V | 補助指標スコア |
| domain | 適用領域カテゴリ |
| theme | 応用テーマカテゴリ |
| pairing | 統合分野の組み合わせ |
| rationale | スコアリングの根拠（1-2文） |
| author_disciplines, method_disciplines, objective_disciplines | Author/Method/Objectiveそれぞれの分野リスト（8分類からの複数選択） |
| author_span, method_span, objective_span, DSI | 各軸の分野横断数と複合指標（Disciplinary Span Index） |
