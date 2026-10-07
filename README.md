# Iron Seed — downloads de teste

Este repositório publica os executáveis de teste do Iron Seed. O código-fonte
do jogo permanece privado. Escolha o pacote da arquitetura do seu computador:

| Sistema | Download |
| --- | --- |
| Windows x64 | [Baixar ZIP](https://github.com/Wilson-Cecchi/Iron-Seed-Downloads/releases/latest/download/IronSeed-Windows-x64.zip) |
| Linux x64 | [Baixar TAR.GZ](https://github.com/Wilson-Cecchi/Iron-Seed-Downloads/releases/latest/download/IronSeed-Linux-x64.tar.gz) |
| macOS Intel | [Baixar ZIP](https://github.com/Wilson-Cecchi/Iron-Seed-Downloads/releases/latest/download/IronSeed-macOS-Intel.zip) |
| macOS Apple Silicon | [Baixar ZIP](https://github.com/Wilson-Cecchi/Iron-Seed-Downloads/releases/latest/download/IronSeed-macOS-AppleSilicon.zip) |

Os links acima apontam sempre para a **Release mais recente**, não
necessariamente para o último commit em desenvolvimento. Consulte as
[notas da Release](https://github.com/Wilson-Cecchi/Iron-Seed-Downloads/releases/latest)
para ver a revisão do código, os testes realizados e os hashes SHA-256.

## Como executar

- **Windows:** extraia todo o ZIP e execute `gdp.exe` dentro de
  `GDP-Windows-x64`. Mantenha `SDL3.dll` e a pasta `ai/` ao lado dele.
- **Linux:** extraia o TAR.GZ, entre em `IronSeed-Linux-x64` e execute `./gdp`.
  O pacote foi compilado no Ubuntu 22.04; requer x64, glibc 2.35 ou uma
  distribuição compatível, e driver com OpenGL 3.3 Core.
- **macOS:** escolha o ZIP correspondente ao chip Intel ou Apple Silicon,
  extraia-o e abra `IronSeed.app`. A versão de teste foi compilada para macOS
  12 ou posterior e requer OpenGL 3.3 Core. O aplicativo ainda não tem
  assinatura Developer ID nem notarização da Apple; o Gatekeeper pode impedir
  a primeira abertura. Leia `README_MACOS.md` incluído no ZIP.

Todos os pacotes incluem os cinco cérebros de IA ativos e exigem um driver com
OpenGL 3.3 Core. A compatibilidade gráfica em diferentes computadores ainda
precisa de playtests; a aprovação da compilação e da inicialização headless na
CI não garante desempenho ou ausência de problemas em todo hardware. Estas são
versões de teste, não o lançamento final do jogo.
