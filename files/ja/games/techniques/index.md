---
title: ゲーム開発テクニック
slug: Games/Techniques
tags:
  - Games
  - Guide
translation_of: Games/Techniques
---
{{GamesSidebar}}

このページでは、オープンウェブ技術を使用してゲームを開発したい人のために、必要不可欠なコア技術をリストアップしています。

- [asm.js 用の非同期スクリプトの使用](/ja/docs/Games/Techniques/Async_scripts)
  - : 特に中規模から大規模のゲームを作成する場合、非同期スクリプトは、ゲームの JavaScript をメインスレッドからコンパイルして、将来のゲーム実行時にキャッシュすることができるため、ユーザーにとって大幅なパフォーマンス向上となるため、活用することが不可欠なテクニックとなります。この記事では、その方法を説明します。
- [起動パフォーマンスの最適化](/ja/docs/Web/Performance/Optimizing_startup_performance)
  - : ゲームをすばやくスムーズに起動させ、ユーザーのブラウザーや機器をロックすることなく表示させる方法。
- [WebRTC のピアツーピアデータチャネルの使用](/ja/docs/Games/Techniques/WebRTC_data_channels)
  - : WebRTC では、音声と映像の通信に対応しているだけでなく、ピアツーピアのデータチャネルを設定して、プレイヤー間でテキストやバイナリーのデータを積極的に交換することができます。この記事では、これで何ができるかを説明し、これを簡単にするライブラリーを使用する方法を紹介します。
- [ウェブゲーム用の効率的アニメーション](/ja/docs/Games/Techniques/Efficient_animation_for_web_games)
  - : この記事では、携帯電話などのローエンド機器に対応しているウェブゲームで効率的にアニメーションを作成するためのテクニックとアドバイスを扱います。CSS の遷移と CSS アニメーション、そして {{ domxref("window.requestAnimationFrame") }} を含む JavaScript のループについて触れます。
- [ウェブゲームの音声](/ja/docs/Games/Techniques/Audio_for_Web_Games)
  - : 音声は、フィードバックや雰囲気を追加するものであり、ゲームにとって重要な要素です。ウェブベースの音声は急速に成熟していますが、まださまざまなブラウザーでの交渉が必要です。この記事では、ウェブゲームに音声を搭載するための詳細なガイドを提供し、可能な限り幅広いプラットフォームで現在動作しているものを見ていきます。
- [二次元の衝突検出](/ja/docs/Games/Techniques/2D_collision_detection)
  - : 2D ゲームにおける衝突検出の簡潔な紹介。
- [タイルマップ](/ja/docs/Games/Techniques/Tilemaps)
  - : タイルは、2Dゲームにおいてゲーム世界を構築するための非常に一般的な手法です。これらの記事は、タイルマップの紹介と、Canvas APIでタイルマップを搭載する方法を提供します。