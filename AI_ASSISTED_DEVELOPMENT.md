# AI-Assisted Development Disclosure

## 日本語

本プロジェクトは**AI支援による開発プロジェクト**です。

### 私が担当したこと

- 「デュアルスクリーン端末で、ゲーム画面とNuzlocke補助情報を分ける」というプロダクトコンセプト
- 手動ルート選択を不要にする自動追従という要件
- AYN Thorをターゲットとする端末・UX方針
- ライブRAMとROM由来データを分離する設計方針
- 読み取り専用、fail-closed、エミュレーションコアを汚染しないという制約
- 実装案の比較、採否判断、反復テスト、動作確認、問題報告
- プロトタイプの範囲と次のマイルストーンの決定

### AIが支援したこと

- mGBA、Qt、libretro、Android周辺コードの調査
- メモリ構造と既存APIの調査・比較
- C/C++、Qt、Java、JNI、CMake、Gradleコードの生成および修正案
- コンパイルエラー、実行時問題、スレッド境界、ビルド設定のデバッグ
- Android移植の足場作りと検証手順
- 技術文書とポートフォリオ文書の草案

### 表示方針

このプロジェクトは、AIの支援を隠したり、すべてのコードを手作業で記述したと主張したりしません。一方で、単なるプロンプト出力でもありません。要件、設計上の制約、製品判断、検証、受け入れ判断に対する責任は私が持ち、AIの出力はレビューと反復を経て採用しています。

## English

This project was developed with substantial AI assistance.

I owned the product concept, requirements, target-device experience, architectural constraints, testing direction, evaluation of alternatives, and acceptance decisions. AI tools assisted with investigating the existing mGBA codebase, proposing and revising implementation code, debugging, build configuration, porting scaffolding, and documentation.

I do not present this as code written entirely by hand. I present it as evidence that I can define a technical product, establish safe boundaries inside an unfamiliar systems codebase, evaluate generated work, test it, identify limitations, and iterate toward a functioning prototype.

