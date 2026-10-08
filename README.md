# Esoteric Ebb - Tradução PT-BR

Tradução de fã do **Esoteric Ebb** para o português do Brasil: diálogos, escolhas, menus, itens, magias e glossário.

📖 **Guia completo na Steam:** [Tradução em Português BR para Esoteric Ebb](https://steamcommunity.com/sharedfiles/filedetails/?id=3754072021)

## ⬇️ Download

Baixe o arquivo `EsotericEbb-PTBR-<versão>.zip` da versão mais recente em **[Releases](https://github.com/AndreCChagas/esoteric-ebb-ptbr/releases/latest)**.

O pacote já vem com o BepInEx (o carregador de mods).

## 🛠️ Instalação

1. Na Steam: botão direito em **Esoteric Ebb** → **Gerenciar** → **Explorar arquivos locais**.
2. Extraia **todo** o conteúdo do ZIP nessa pasta (onde está `Esoteric Ebb.exe`) e substitua os arquivos.
3. Abra o jogo. A **primeira** abertura demora alguns minutos enquanto o BepInEx se prepara.

**Steam Deck:** no Modo Desktop, extraia o ZIP na pasta do jogo e, em **Propriedades → Geral → Parâmetros de Inicialização**, cole:

```
WINEDLLOVERRIDES="winhttp=n,b" %command%
```

### Joga no beta "localization" da Steam?

O beta tem um sistema de idiomas oficial. Para ele há um pacote **sem BepInEx**: baixe o `EsotericEbb-PTBR-BETA-CSV-<versão>.zip` na [página de versões](../../releases/latest), extraia em `Esoteric Ebb_Data\StreamingAssets\Localization` e escolha **"Português (BR)"** em Options > Language.

### Atualizando da 2.0 a 2.3

A partir da 2.4 o pacote traz um BepInEx mais novo (**be.788**), necessário para a atualização do jogo com o novo sistema de idiomas.

1. Na pasta do jogo, **apague** as pastas `BepInEx\core` e `dotnet` (as pastas `BepInEx\plugins` e `BepInEx\config` podem ficar).
2. Extraia o ZIP novo na pasta do jogo e substitua os arquivos.
3. Abra o jogo. A primeira abertura volta a demorar alguns minutos.

> **Trocou o jogo de ramo na Steam** (normal ↔ beta)? A Steam apaga o BepInEx e a tradução. Basta extrair o ZIP de novo.

### ⚠️ Atualizando da versão 1.0.x

A versão 2.0 usa um plugin novo. Faça uma **instalação limpa**:

1. Na pasta do jogo, **apague** a pasta `BepInEx`, a pasta `dotnet`, `winhttp.dll`, `doorstop_config.ini` e `Untranslated.txt` (se existir).
2. Extraia o ZIP novo na pasta do jogo.
3. Abra o jogo (a primeira abertura volta a demorar alguns minutos).

> **Usa outros mods?** Apagar a pasta `BepInEx` remove todos eles. Nesse caso, apague só a pasta `BepInEx\plugins\EsotericEbbBR` e extraia o ZIP por cima. Se o plugin antigo ficar na pasta por engano, o novo o desativa sozinho na primeira abertura; feche e abra o jogo de novo.

**Desinstalar:** apague `BepInEx\plugins\EsotericEbbPTBR`. Para remover o BepInEx também, apague `BepInEx`, `dotnet`, `winhttp.dll` e `doorstop_config.ini`.

## 🐞 Encontrou um erro?

Abra uma **[Issue](https://github.com/AndreCChagas/esoteric-ebb-ptbr/issues/new/choose)** com:

- um print da tela;
- a versão da tradução;
- se puder, o arquivo `BepInEx\LogOutput.log`.

## 🙏 Créditos

- **Tradução PT-BR e plugin:** SirChagas
- **Agradecimento:** clarkkent - [boosty.to/clarkkent](https://boosty.to/clarkkent), autor do mod russo que deu origem a este projeto
- **[BepInEx](https://github.com/BepInEx/BepInEx)** (LGPL-2.1)

*Esoteric Ebb* é propriedade de seus desenvolvedores. Esta é uma tradução feita por fãs, gratuita e sem fins lucrativos.
