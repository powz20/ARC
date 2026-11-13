# Avisos de terceiros

## Terminal (terminal-emulator e terminal-view)

Os módulos `terminal-emulator/` e `terminal-view/` são copiados do projeto
[termux/termux-app](https://github.com/termux/termux-app) (versão 0.119.0-beta.3),
que por sua vez usa código de [Android-Terminal-Emulator](https://github.com/jackpal/Android-Terminal-Emulator)
(jackpal), licenciado sob a **Apache License 2.0**.

Os módulos foram adaptados para o Android Gradle Plugin 8 (namespace, remoção de publicação e testes).
O restante do Termux (app, termux-shared) **não** foi copiado.

Texto completo da licença: https://www.apache.org/licenses/LICENSE-2.0

## Bibliotecas

- lz4-java (at.yawk.lz4), Apache 2.0
- Apache Commons Compress, Apache Commons Lang, Apache 2.0
- XZ for Java (org.tukaani), Public Domain
- Commons IO, Apache 2.0
- AndroidX Annotation, Apache 2.0
