# Transdisciplinary Engineering 文献評価結果サマリー

対象: [評価指標（rubric.md）](../evaluation/rubric.md) に基づき評価した122件（ISTE/ISPE TE国際会議論文集 2016–2025年：102件、関連ジャーナル論文：20件）。
データ: [評価済みデータセット（CSV）](../evaluation/te_papers_evaluated.csv) / [インタラクティブマッピング](./te_mapping.html)

## 1. 全体傾向

| 指標 | 平均 | 最小 | 最大 |
|---|---|---|---|
| G（目標特性） | 2.93 | 1 | 5 |
| C（協働特性） | 3.20 | 1 | 5 |
| I（統合特性） | 2.93 | 1 | 4 |
| **TE-Index（総合）** | **3.01 / 5** | **1.0** | **4.7** |
| M（方法論的貢献） | 2.97 | 1 | 5 |
| V（実証水準） | 2.21 | 1 | 4 |

- **V（実証水準）が最も低い平均値**であり、TEを標榜する研究の多くが概念提示・単一ケース紹介にとどまり、複数ケースや定量的効果測定を伴う実証研究が相対的に少ないことを示す。
- G・C・Iの中では**C（協働の幅）が最も高い**が、5点満点中3.2程度であり、真に社会・産業・市民を巻き込んだ共創（レベル5）はむしろ少数派で、大半は工学内または工学×経営の連携にとどまる（後述の pairing 分布参照）。

## 2. 「TEらしさ」の高い論文・低い論文

**TE-Index上位（4.3以上）**は、いずれも実世界の wicked problem（地域エネルギー政策、システミックリスク、水資源管理、義肢工学、規制変更対応、コミュニティ開発）を対象に、多様なステークホルダーとの共創・長期実証を伴う点で共通する。

**TE-Index下位（2.0以下）**は、①タイトルに"transdisciplinary"を含みながら実態は単一分野（情報工学・機械工学）の技術論文、②既存研究のレビュー・ビブリオメトリック分析、のいずれかに分類される。**"transdisciplinary"という語のラベル使用と、実際のTE実践の間に乖離がある**ことが本評価の重要な発見の一つである（Lattanzio et al. 2020の"TREND"研究群も同様の問題意識から、既存デザインツール41種のうち真にTDと呼べるものは皆無と報告している）。

## 3. カテゴリ分布

- **Domain**: Research 67 / Practice 34 / Multiple 14 / Education 7 — 教育（TDEE）に関する研究は相対的に少なく、Wognum et al. (2019) が指摘した研究アジェンダの中でも教育領域の手薄さが継続している可能性。
- **Application Theme**: Design Methodology(25) > Other(19) > Industry 4.0(15) ≈ Sustainability/Resilience(15) > PLM(12) ≈ Systems Engineering(12) > Education(11) > Social Innovation(8) > Digital Twin(5)
- **Disciplinary Pairing**: Engineering×Management(38) ≈ Engineering×Social Science(38) > Engineering×Engineering(25) > Engineering×Data Science(12) > Other(9) — 工学と経営・社会科学の連携が中心で、データサイエンスとの融合はまだ発展途上。

## 4. 年次推移（ISTE/ISPE TE会議 2016–2025）

平均TE-Indexは2016年の2.75から2025年の3.23へと緩やかに上昇しており、会議シリーズが「Transdisciplinary Engineering」に改称された2016年以降、実践の深化（特にCollaboration・Integrationの充実）が進んでいる傾向がうかがえる。ただし年ごとの変動もあり、単調な改善ではない。

## 5. 示唆

1. **「TE」を名乗る研究の質保証にはV（実証水準）の底上げが課題**。概念提案にとどまる論文が多く、複数ケース・定量評価を伴う研究の蓄積が今後の発展に必要。
2. **Engineering×Social Scienceのペアリングは全体の3割超**を占め、TEの定義（自然科学と社会科学の統合）は実践においてもある程度反映されているが、依然としてEngineering×Engineering（工学内統合）を「TE」とラベリングする例も多く、Multidisciplinary/Interdisciplinaryとの境界の曖昧さが実務上の課題として残る。
3. **マッピング（インタラクティブアーティファクト）** ではDomainフィルタや個別論文の評価根拠を確認できるため、特定の応用領域（例：Sustainability/Resilience）における高TE-Index事例のベストプラクティス抽出などに活用できる。

## 6. 分野横断度（Author / Method / Objective）の分析

[ルーブリック追加指標](../evaluation/rubric.md#追加指標分野横断度author--method--objective--add-on)に基づき、Author（著者）・Method（手法）・Objective（目的）それぞれが8分類の学問分野をどれだけ跨いでいるかを評価した（インタラクティブな可視化は[マッピングアーティファクト](./te_mapping.html)の「分野横断度」カードを参照）。

| 軸 | 平均span | 内訳（1分野／2分野／3分野以上） |
|---|---|---|
| Author（著者） | 1.52 | 59 ／ 62 ／ 1 |
| Method（手法） | 1.81 | 34 ／ 77 ／ 11 |
| Objective（目的） | 1.86 | 33 ／ 74 ／ 15 |

**平均DSI（Disciplinary Span Index） = 1.73 / 最大8/3≈2.67**

- **Objective（目的）が最も分野を跨ぎやすく、Author（著者）が最も跨ぎにくい**という非対称な傾向が明確に見られる。多くの論文は「著者は工学単独」でありながら「目的は工学＋社会科学・経営学」を志向しており、**著者構成の学際化が目的設定の学際性に追いついていない**ことを示唆する。
- 分野別出現数（Author／Method／Objective）：Engineering は全軸で圧倒的多数（119／98／115件）を占める一方、**Social Scienceは著者としては14件しか登場しないのに、手法として38件、目的として40件登場**しており、TE論文の多くが「社会科学的な視点や手法を、社会科学者を伴わずに工学研究者だけで扱おうとしている」実態を表している。
- DSIとTE-Index（既存の中核指標）の間には正の相関が見られ（DSI≈1の論文群の平均TE-Indexは2.51、DSI≈2の論文群は3.17）、分野横断度の高さが「TEらしさ」の実践度と整合していることが確認できる。これは2つの独立した指標体系が同じ現象を異なる角度から捉えていることの傍証となる。
- DSI最高値（2.67）はC2-025「Towards a Transdisciplinary Approach to Systemic Risk Detection」とJ-017「Editorial: Transdisciplinary engineering for sustainability decisions」で、いずれもAuthor/Method/Objectiveの全軸で複数分野にまたがる。

## 7. 制約・留意事項

- 収集はWeb検索経由でアクセス可能な範囲（IOS Press ebooks / Google Scholar経由の公開情報）に限定。網羅的な系統的レビューではなく、中規模サンプル（122件）による傾向把握である。
- ペイウォール論文（主にジャーナル論文20件中19件）は要旨のみでの評価となっており、本文精査に基づく評価より確度が低い可能性がある。
- スコアリングは4つの評価者（LLMエージェント）がバッチ分担して実施しており、ルーブリックは共通だが、評価者間の厳密なキャリブレーション（相互採点一致率の検証）は未実施。境界線上の判断（各batchのagentが報告した"ambiguous cases"）については個別に一覧を参照可能。
