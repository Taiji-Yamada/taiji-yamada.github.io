---
layout: page
title: 脳の多様なタイムスケールを深堀するための作戦会議＃１
date: 2026-11-05
description: 脳のタイムスケールに関するどんな論文を読んでいくかの方針を決定する
tags: [timescale]
categories: 思考
published: true
---

<style>
  .post-content h2 {
    margin-top: 2.5rem;
    padding-bottom: 0.3rem;
    border-bottom: 2px solid var(--global-theme-color);
  }
  .post-content h3 {
    margin-top: 1.8rem;
    padding-bottom: 0.2rem;
    border-bottom: 1px solid var(--global-divider-color);
  }
</style>

## 脳のタイムスケール
脳は多様なタイムスケールを持っている。脳が環境から推定しなければならない変数は山ほどあるが，短いタイムスケールから推定すべき変数もあれば，長いタイムスケールから推定すべき変数もあるだろう。だから脳も同じように複数のタイムスケールを持っているのだと思う。私の研究にも非常に重要なテーマだと思うのだが，あまり知識がないので，ここで一度腰を上げてレビューする必要があるように思った。

## 方針
おそらく３つの観点について知る必要がある。これらに関する論文をclaude君に列挙してもらって，読んでいく。
1. 脳のタイムスケールはどのようになっているか
2. 脳のタイムスケールによって何が可能になるか
3. 脳のタイムスケールはどのように生まれるか

### 脳のタイムスケールはどのようになっているか
- Murray et al.(2014). A hierarchy of intrinsic timescales across primate cortex.
  - この分野の走り。スパイクの自己相関から感覚野は短く，前頭前野は長いという階層性を示した。
- Hasson et al. (2008) A Hierarchy of Temporal Receptive Windows in Human Cortex.
- Honey et al. (2012) Slow cortical dynamics and the accumulation of information over long timescales.
  - ヒトの脳のタイムスケールの階層性を示した。
- Gao et al. (2020) Neuronal timescales are functionally dynamic and shaped by cortical microarchitecture.
  - タイムスケールが課題に応じて動的に変わることを示した。
- Raut et al. (2020) Hierarchical dynamics as a macroscopic organizing principle of the human brain.
  - BOLD信号の自己相関から大域的なタイムスケールの階層性を示した。
- Ito et al. (2020) A cortical hierarchy of localized and distributed processes revealed via dissociation of task activations, connectivity changes, and intrinsic timescales.
  - intrinsic timescaleと課題活動・結合性の関係を調べた。
- Shafiei et al. (2020) Topographic gradients of intrinsic dynamics across neocortex.
  - intrinsic timescaleの皮質勾配を示した。
- Manea et al. (2022) Neural timescales reflect behavioral demands in freely moving rhesus macaques.
  - マカクの全脳fMRIで，線条体や小脳を含む皮質下までタイムスケールを推定した。claude曰く，皮質-線条体-小脳回路を扱うなら必読らしい。
- Zeraati et al. (2022) A flexible Bayesian framework for unbiased estimation of timescales.
  - 自己相関によるタイムスケール推定のバイアスをベイズ的に補正する手法。

## 脳のタイムスケールによって何が可能になるか
- Wolff et al. (2022) Intrinsic neural timescales: temporal integration and segregation.
  - 「長いタイムスケールは時間的統合，短いタイムスケールは分離を担う」というレビュー。
- Cavanagh et al. (2020) A diversity of intrinsic timescales underlie neural computations.
  - 単一ニューロンレベルのタイムスケールの多様性と，意思決定・価値計算との関係のレビュー。
- Soltani et al. (2021) Timescales of cognition in the brain.
  - 報酬学習とタイムスケールの関係に関するレビュー。
- Bernacchia et al. (2011) A reservoir of time constants for memory traces in cortical neurons.
  - 報酬履歴を多様な時定数で保持するニューロン集団を示した。この集団から，環境に合った統合窓を読み出せる。
- Spitmaan, Seo, Lee, Soltani (2020) Multiple timescales of neural dynamics and integration of task-relevant signals across cortex.
  - 報酬・選択履歴の統合されたタイムスケールが，領域ごと・ニューロンごとに異なることを示した。
- Iigaya et al. の一連の研究
  - 複数の時間スケールのシナプス可塑性があれば，volatilityに適応的に学習率を調整できることを示した。
- Hasson et al. (2015) Hierarchical process memory.
  - 時間的受容窓（temporal receptive window）の階層を，記憶を処理の一部とみなすレビュー。
- Tanaka et al. (2004) Prediction of immediate and future rewards differentially recruits cortico-basal ganglia loops.
  - fMRIで、線条体の腹側から背側にかけて報酬割引の時間スケールが勾配をなすことを示した。
- Masset et al.（2025） Multi-timescale reinforcement learning in the brain.
  - これはもう読んだ。
- Perez-Nieves et al. (2021) Neural heterogeneity promotes robust learning.
  - 時定数が不均一であること自体が学習を頑健にする。

## 脳のタイムスケールはどのように生まれるか
- Chaudhuri et al. (2015) A Large-Scale Circuit Mechanism for Hierarchical Dynamical Processing in the Primate Cortex.
  - 興奮性の勾配と長距離結合から階層が生じる。
- Wang (2020) Macroscopic gradients of synaptic excitation and inhibition in the neocortex.
  - シナプスの興奮・抑制の感覚野から連合野へ連続的な勾配が，タイムスケールの階層やワーキングメモリといった機能の違いを生んでいる。
- Kiebel et al. (2008) A hierarchy of time-scales and the brain.
  - ベイズ的な生成モデルの観点からタイムスケールの階層を論じた。
