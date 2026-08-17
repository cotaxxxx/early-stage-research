# Early Stage Research

査読前の独立研究ノート、証明草稿、再現計算資料、専門家引継ぎ文書をまとめるリポジトリです。

## Research map

| # | Project | Role | Current status |
|---|---|---|---|
| 01 | [Dual-Phase Deficit](./dual-phase-deficit/) | 2次元・長方形族の双対位相欠損 | v1.2.1 Expert Handoff。外部逐行査読・優先性監査待ち |
| 02 | [D3 Model](./d3-model/) | 3次元・立方体の最適双対回転 | v1.0 Expert Handoff。四次主モードは厳密、全欠損の大域最小性は未証明 |
| 03 | [Rotational Dual Geometry](./rotational-dual-geometry/) | 2D→高次元を束ねる総合研究計画 | v1.1 Final Handoff。総合ノートとして閉鎖 |
| 04 | [Rounded D3-Bicone Supplement](./rounded-d3-bicone/) | O(2)→D3 分裂論文の再現・認証資料 | Supplement / reproducibility package |

## Intended file layout

```text
early-stage-research/
├── README.md
├── SHA256SUMS.txt
├── dual-phase-deficit/
│   ├── README.md
│   ├── SHA256SUMS.txt
│   └── paper/
│       └── dual_phase_deficit_v1.2.1_citation_corrected_ja.pdf
├── d3-model/
│   ├── README.md
│   ├── SHA256SUMS.txt
│   └── paper/
│       └── D3_model_hypothesis_paper_v1.0_ja.pdf
├── rotational-dual-geometry/
│   ├── README.md
│   ├── SHA256SUMS.txt
│   └── paper/
│       └── rotational_dual_geometry_v1.1_final_ja.pdf
└── rounded-d3-bicone/
    ├── README.md
    ├── SHA256SUMS.txt
    └── supplement/
        └── Furuta_Bicone_D3_Supplement.zip
```

## Relationship of the four items

`Dual-Phase Deficit` は2次元の技術モデル、`D3 Model` は3次元への拡張モデル、`Rotational Dual Geometry` はそれらを接続する総合ノートです。`Rounded D3-Bicone Supplement` は別系統の認証・再現資料として管理します。

## Verification

各プロジェクトの `SHA256SUMS.txt` に加えて、ルートの [`SHA256SUMS.txt`](./SHA256SUMS.txt) に4ファイルのハッシュを集約します。

## Review status

このリポジトリの資料は、個別READMEで明示しない限り査読前の研究途中資料です。数学的主張、優先性、用語、投稿形態の最終判断は外部専門家による確認を前提とします。
