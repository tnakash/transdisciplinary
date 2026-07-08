# Transdisciplinary Engineering (TE) の定義と構成要素の構造化

## 1. 背景：Concurrent Engineeringからの進化

Transdisciplinary Engineering (TE) は、1980年代に発展した **Concurrent Engineering (CE)** の基本概念を拡張・進化させた新興分野である。

- CEを推進してきた学会 ISPE, Inc.（International Society of Productivity Enhancement）は、学際性の重要性の高まりを受けて2016年に会議シリーズ名を「Transdisciplinary Engineering」に変更し、2017年に学会自体を **ISTE（International Society of Transdisciplinary Engineering）** に改称した。
- CEが「企業内・企業間の協働と、それに関わる多様な要素（人・プロセス・組織）の統合」に焦点を当てるのに対し、TEはそれを土台としつつ、**自然科学（工学）と社会科学の知識を統合**し、より広範な現代社会の複雑な課題に対応する点で発展的である。

出典: [ISTE – About](https://intsoctransde.org/about/), [TE2024 – What is TE?](https://www.te2024.org.uk/about/what-is-te), [TE2022 – Transdisciplinary Engineering](https://www.te2022.org/transdisciplinary-engineering)

## 2. 学際性の階層：Multi / Inter / Transdisciplinary

一般的な学際性研究の分類（Nicolescu, Klein等）に基づくと、統合の度合いは以下のように階層化される。TEはこの中で最も統合度の高い水準に位置づけられる。

| レベル | 定義 | 知識の関係 |
|---|---|---|
| Multidisciplinary | 複数分野の視点から問題を並列に検討するが、統合はしない | 並置（juxtaposition） |
| Interdisciplinary | 複数分野の方法・理論・ツールを転移・統合し、統一的理解を作る | 相互作用（interaction） |
| Transdisciplinary | 学問分野の存在論・認識論の境界を超え、学術知と実践知（社会・産業・ユーザー）を統合する | 真の統合・共創（synthesis / co-creation） |

出典: [Nicolescu – Methodology of Transdisciplinarity](https://www.researchgate.net/publication/268353025_Methodology_of_Transdisciplinarity-Levels_of_Reality_Logic_of_the_Included_Middle_and_Complexity), Klein (interdisciplinarity/transdisciplinarity比較)

## 3. TE研究における定義の収斂：3つの中核特性

TE分野で最も体系的に「定義」を扱った実証研究が Lattanzio, Newnes, Parry & Nassehi (2021), *"Concepts of transdisciplinary engineering: a transdisciplinary landscape"*, *International Journal of Agile Systems and Management*, 14(2), 292-312 である。

この研究はISTE国際会議（TE2020）の著者34名への調査に基づき、「単一の定義は存在せず、TEは3つの特性軸からなる "landscape（景観）" として捉えるべき」と結論づけた。3つの特性は参加者の91%が言及した中核概念である。

1. **Goal（目標）**：何を目指す研究か（例：ill-defined/wicked problemの解決、社会的関連性、イノベーション創出）
2. **Collaboration（協働）**：誰と、どのように協働するか（分野横断的な専門家、産学連携、ユーザー・社会との共創）
3. **Integration（統合）**：知識・方法論・プロセスをどう統合するか（並置的か、真に統合的か）

Wognum, Bil, Elgh, Peruzzini, Stjepandić & Verhagen (2019), *"Transdisciplinary systems engineering: implications, challenges and research agenda"*, *IJASM*, 12(1), 58-89 も同様に、TEを「ill-definedで社会的に重要な問題を解くプロセス」と位置づけ、研究・実務・教育の3領域における課題を整理している。

## 4. TEの作業定義（本プロジェクトにおける統合定義）

以上の文献レビューを踏まえ、本プロジェクトでは以下を **Transdisciplinary Engineeringの作業定義** とする。

> Transdisciplinary Engineering (TE) とは、Concurrent Engineeringを基盤としつつ、自然科学（工学）と社会科学の知識・方法論を、学術・産業・社会の多様なステークホルダーとの協働を通じて統合し、単一の専門分野では解決しえない ill-defined かつ社会的関連性の高い課題（製品・プロセス・組織・社会システムに関わるイノベーション）に取り組む研究・実践・教育のアプローチである。

## 5. 構成要素の構造化（フレームワーク）

3つの中核特性（Goal / Collaboration / Integration）を主軸に、文献から抽出した下位要素を以下のように構造化する。

```
Transdisciplinary Engineering
│
├── A. Goal（目標特性）
│   ├── A1. 問題の性質（ill-defined / wicked problem か、構造化された問題か）
│   ├── A2. 社会的関連性（社会・環境・経済へのインパクトの明示性）
│   └── A3. イノベーション文脈（製品・プロセス・組織・社会環境のいずれを対象とするか）
│
├── B. Collaboration（協働特性）
│   ├── B1. 分野横断の幅（工学内の複数専門分野 ／ 工学×社会科学・人文科学）
│   ├── B2. ステークホルダーの多様性（学術・産業・行政・市民・エンドユーザー）
│   └── B3. ユーザー・実践者の参加様式（受動的情報提供 ／ 共創・共同設計）
│
├── C. Integration（統合特性）
│   ├── C1. 知識統合の深さ（並置 → 相互参照 → 真の統合）
│   ├── C2. 方法論・ツール（Mixed methods, ライフサイクル統合, PLM/PCP統合等）
│   └── C3. プロセス統合（製品創出プロセス内での早期・並行的統合）
│
└── D. 適用領域とコンテキスト（Wognum et al. 2019の3領域 + 応用テーマ）
    ├── D1. 研究（Research）：理論・フレームワーク構築
    ├── D2. 実務（Practice）：産業応用・ケーススタディ
    ├── D3. 教育（Education）：TE人材育成・カリキュラム
    └── D4. 応用テーマ例：Industry 4.0、社会イノベーション、レジリエンス、
        持続可能なモビリティ、複雑な社会技術システム
```

## 6. 参考文献（一次資料）

- Lattanzio, S., Newnes, L., Parry, G., & Nassehi, A. (2021). Concepts of transdisciplinary engineering: a transdisciplinary landscape. *International Journal of Agile Systems and Management*, 14(2), 292-312.
- Wognum, N., Bil, C., Elgh, F., Peruzzini, M., Stjepandić, J., & Verhagen, W. J. C. (2019). Transdisciplinary systems engineering: implications, challenges and research agenda. *International Journal of Agile Systems and Management*, 12(1), 58-89.
- ISTE (International Society of Transdisciplinary Engineering). https://intsoctransde.org/about/
- TE2024 Conference. What is TE? https://www.te2024.org.uk/about/what-is-te
- TE2022 Conference. Transdisciplinary Engineering. https://www.te2022.org/transdisciplinary-engineering
- Nicolescu, B. Methodology of Transdisciplinarity – Levels of Reality, Logic of the Included Middle and Complexity.
