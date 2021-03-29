Sodium Practice
===

## Sodiumについて

https://github.com/kanengomibako/Sodium


## ファイル・ディレクトリ構成

```
（STM32CubeIDEプロジェクトファイル）
├── .cproject
├── .project

（CubeMX自動生成ファイル）
├── Core（ソースコード）
│   ├── Inc（*.hファイル）
│   ├── Src（*.cファイル）
│   └── Startup（*.sファイル）
├── Drivers（STM32ドライバファイル）
├── Middlewares（FreeRTOSなど）
├── STM32F722RCTX_FLASH.ld（FLASH設定）
├── STM32F722RCTX_RAM.ld（RAM設定）
├── Sodium_practice.ioc（自動生成の元となるファイル）

（自作ソースコード）
├── User（ソースコード）

（上記とは無関係のファイル）
├── Doxyfile（doxygen設定）
├── README.md（このファイル）
├── cmake（CMake関連・STM32CubeIDEを使わずにビルドするために用意）
├── .clang-format（clang-format設定）
└── format.sh（clang-format実行スクリプト）
```
