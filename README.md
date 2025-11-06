🌀 SusanooOS — Prototype Phase 01

神話と技術の融合を目指す、次世代OSプロジェクト

🌅 概要

SusanooOS（スサノオOS）は、
日本神話の荒ぶる力「スサノオ」の名を冠した、
独自カーネルを目指すグラフィカルOSプロジェクトです。

現在は開発初期段階として、
FreeBSDカーネルをベースにしたデモ版OSの構築を進めています。
最終的には独自カーネルへ移行し、
UEFI/EDK2を通じて完全自作ブート環境を実現します。

🧩 開発ステージ
フェーズ	内容	状況
Phase 0	開発環境構築 (Debian + EDK2 + QEMU)	✅ 完了
Phase 1	FreeBSDベース デモOS構想	🌀 進行中
Phase 2	GUIシェル（グラフィカル環境）設計	🕓 準備中
Phase 3	独自カーネル設計 (Susanoo Core)	🔮 未来
Phase 4	完全UEFI自作ブート	🔮 未来

🧠 開発哲学

「荒ぶる力を、秩序に変える。」

SusanooOSは、
神話的テーマ × 現代OS設計 を融合したプロジェクトです。
見た目の美しさと技術的挑戦を両立し、
開発者自身が“創造する喜び”を感じられる環境を目指します。

🧰 開発環境

OS: Debian 13 (trixie)

ハードウェア: HP EliteBook G1 (Intel Core m7-6Y75 x4)

開発ツール:

GCC, NASM, Python3

QEMU / OVMF (UEFIブート検証)

EDK2 BaseTools

Git + GitHub SSH連携済み

⚙️ ビルド方法（BaseTools構築）
cd edk2
make -C BaseTools
source edksetup.sh

🧱 ディレクトリ構成（例）
SusanooOS/
├─ edk2/               # EDK2 Core & BaseTools
├─ susanoo-kernel/     # 独自カーネル実験用
├─ susanoo-gui/        # GUIデモ環境（予定）
├─ docs/               # 設計ノート・仕様書
├─ scripts/            # ビルド/起動用スクリプト
└─ README.md

🌐 リンク

GitHub: https://github.com/munehiro/SusanooOS
開発ノート: （準備中）

🪶 作者

Munehiro Yoshida

"From myth to machine — awaken the Susanoo."
