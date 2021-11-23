# 苦しんで覚える計算機アーキテクチャ Learning Computer Architecture with sweat

code-base for suffering architecture

## 目指すべきところ Our goal

情報技術を支える要素を自作して原理を学ぶ。

「どのレベルで作るの？」 -> CPU から！

Learning fundamental principles in information technology by DIY.

"What specific level would you like to start?" "OFF COURSE, FROM CPU."

## ロードマップ Road Map

1. RISC-V のアセンブリが動作する環境とハードウェアを作る
	1. RISC-V アセンブリインタープリタ (asm)
    2. RISC-V アセンブラ (asm -> bin)
    3. RISC-V CPU コア (SystemVerilog)
2. 高級言語で開発する環境を作る
    1. C 言語コンパイラ (C -> asm)
3. 画面描写を作る
    1. 映像制御ハードウェア
    2. VRAM ドライバ
4. TCP/IP スタックを作る
    1. TCP/IP プロトコルスタック 
    2. HTTP GET メソッド
    3. Ethernet ドライバ
    4. 割込みコントローラ
    5. HTTP サーバ in Raspberry Pi
5. TCP/IP ライブラリを移植する (LwIP もしくは uIP)
6. OS を搭載
7. HTTP サーバからストリーミングで画面描写

1. Construct development environment and hardware for running RISC-V assembly language
    1. Interpreter for RISC-V assembly language
    2. Assembler for RISC-V (asm -> bin)
    3. RISC-V CPU core in SystemVerilog
2. Designing High-level language compiler for RISC-V
    1. C-language compiler for RISC-V
3. Adding display driver
    1. Video control hardware
    2. VRAM driver
4.  Adding TCP/IP stack
    1. TCP/IP protocol stack
    2. HTTP GET method
    3. Ethernet driver
    4. Interrupt controller
    5. HTTP server in Raspberry Pi
5. Porting TCP/IP library (LwIP or uIP)
6. Porting OS
7. Display video streaming from HTTP server