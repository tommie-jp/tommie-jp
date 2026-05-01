# About Tommie.jp

[English](README.md) | [日本語](README.ja.md)

[![GitHub](https://img.shields.io/badge/GitHub-@tommie--jp-181717?logo=github)](https://github.com/tommie-jp)

<div align="right">更新日: 2026-05-02</div>

- AIコーディング
  - [![Claude Code](https://img.shields.io/badge/-Claude%20Code-D97757?logo=anthropic&logoColor=white)](https://www.anthropic.com/claude-code)
で 今まで面倒で 作らなかった/作れなかった アプリが作れるようになって、プログラマー人生で今が一番楽しい。
- 私のテーマ
  - リアルタイムで動くWebサイト
    - 現在、MMO(tommieChat)を作っています。
  - [![Soft-FPGA](https://img.shields.io/badge/-Soft--FPGA-4A90E2?logoColor=white)](https://github.com/tommie-jp/Soft-FPGA-Reversi)
    - 私が提唱している [verilog](https://ja.wikipedia.org/wiki/Verilog) ソースを [Verilator](https://verilator.org/) で C++ ソースへ変換し、マイコン上で実行する技術

- アナログ回路(勉強中)
  - RF 回路に興味があります。
  - LTspice でシミュレーションするのが大好きです。
  - 目標は自作回路で送受信機を作製すること。

- 資格
  - [第一種情報処理認定](https://www.ipa.go.jp/shiken/kubun/old.html)
    - 現代の[応用情報技術者試験（AP）](https://www.ipa.go.jp/shiken/kubun/ap.html)に相当
  - [第二級アマチュア無線技士](https://www.nichimu.or.jp/denpa/shikaku/ama/index.html)
    - 開局はまだしてないです。(したい)
  - [電験三種](https://www.shiken.or.jp/chief/third/)を勉強中。

- 英語
  - 英文のIT技術書は読めます。日常会話もOKですが、ビジネスでは厳しいかも。

## 🛠 主なプロジェクト

- **[tommieChat](https://github.com/tommie-jp/tommie-chat)** — ブラウザで動く 3D MMO チャット (Babylon.js + Nakama サーバ)。かつて人気だったアメーバ Pigg をリスペクト
- **[Reversi UART Protocol](https://github.com/tommie-jp/reversi-uart-protocol)** — 自作 CPU を PC に UART 接続するためのプロトコル仕様の提案
- **[Soft-FPGA-Reversi](https://github.com/tommie-jp/Soft-FPGA-Reversi)** — Verilog で書いたリバーシ専用アクセラレータを Verilator 経由で Raspberry Pi Pico 2 上で動かす実装
- **[Soft-FPGA-TD4](https://github.com/tommie-jp/Soft-FPGA-TD4)** — 4 ビット CPU "TD4" を Verilog で記述し、Verilator で Raspberry Pi Pico 2 上に実装
- **[curve-tracer](https://github.com/tommie-jp/curve-tracer)** — トランジスタ／FET 用カーブトレーサ

## 🧰 技術スタック

### Web 系

[![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/ja/)
[![Babylon.js](https://img.shields.io/badge/Babylon.js-3D%E3%83%A9%E3%82%A4%E3%83%96%E3%83%A9%E3%83%AA-BB464B?logo=babylondotjs&logoColor=white)](https://www.babylonjs.com/)
[![WebSocket](https://img.shields.io/badge/-WebSocket-010101?logoColor=white)](https://ja.wikipedia.org/wiki/WebSocket)
[![PHP](https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white)](https://www.php.net/)

### サーバサイド

[![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Deno](https://img.shields.io/badge/-Deno-000000?logo=deno&logoColor=white)](https://deno.com/)
[![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Nakama](https://img.shields.io/badge/-Nakama-8A2BE2?logoColor=white)](https://heroiclabs.com/nakama/)
[![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white)](https://go.dev/)

### 組み込み

[![C](https://img.shields.io/badge/-C-A8B9CC?logo=c&logoColor=white)](https://ja.wikipedia.org/wiki/C%E8%A8%80%E8%AA%9E)
[![C++](https://img.shields.io/badge/-C%2B%2B-00599C?logo=cplusplus&logoColor=white)](https://ja.wikipedia.org/wiki/C%2B%2B)
[![FPGA](https://img.shields.io/badge/-FPGA-007ACC?logo=xilinx&logoColor=white)](https://ja.wikipedia.org/wiki/FPGA)
[![Verilog](https://img.shields.io/badge/-Verilog-1B6FCB?logoColor=white)](https://ja.wikipedia.org/wiki/Verilog)
[![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-1B6FCB?logoColor=white)](https://ja.wikipedia.org/wiki/SystemVerilog)

[![Soft-FPGA](https://img.shields.io/badge/-Soft--FPGA-4A90E2?logoColor=white)](https://github.com/tommie-jp/Soft-FPGA-Reversi) — 私が開発、提唱している [verilog](https://ja.wikipedia.org/wiki/Verilog) ソースを [Verilator](https://verilator.org/) で C++ ソースへ変換し、マイコン上で実行する技術

### アナログ回路 / PCB

[![LTspice](https://img.shields.io/badge/-LTspice-005377?logo=analogdevices&logoColor=white)](https://www.analog.com/jp/resources/design-tools-and-calculators/ltspice-simulator.html)
[![KiCad](https://img.shields.io/badge/-KiCad-314CB0?logo=kicad&logoColor=white)](https://www.kicad.org/)

### ツール / AI

[![Claude Code](https://img.shields.io/badge/-Claude%20Code-D97757?logo=anthropic&logoColor=white)](https://www.anthropic.com/claude-code)
[![WSL2](https://img.shields.io/badge/-WSL2-0078D6?logo=linux&logoColor=white)](https://learn.microsoft.com/ja-jp/windows/wsl/)
[![VSCode](https://img.shields.io/badge/-VSCode-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)
[![VirtualBox](https://img.shields.io/badge/-VirtualBox-183A61?logo=virtualbox&logoColor=white)](https://www.virtualbox.org/)
[![MSYS2](https://img.shields.io/badge/-MSYS2-1F2937?logo=msys2&logoColor=white)](https://www.msys2.org/)


## 🌐 リンク

- GitHub: [@tommie-jp](https://github.com/tommie-jp)
- X: [@tommie_nico](https://x.com/tommie_nico)
- Email: [open.tommie@gmail.com](mailto:open.tommie@gmail.com)
