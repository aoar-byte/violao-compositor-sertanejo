# 🎸 Violão Compositor Sertanejo Pro v2.3.0

**Ferramenta em desenvolvimento de auxílio para composição musical com violão digital — para músicos, cantores, compositores e iniciantes.**

[![Versão](https://img.shields.io/badge/versão-2.3.0-blue)](https://github.com/seu-usuario/violao-compositor)
[![Licença](https://img.shields.io/badge/licença-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/status-estável-brightgreen)]()

🔗 **Acesso rápido:** Basta abrir o arquivo `index.html` em qualquer navegador moderno. **Zero instalação, zero configuração.**

---

## 📋 **Índice**

- [🎯 O que é?](#-o-que-é)
- [👥 Para quem é?](#-para-quem-é)
- [⚡ Funcionalidades](#-funcionalidades)
- [🚀 Como usar](#-como-usar)
  - [Primeiro acesso](#primeiro-acesso)
  - [Modo CifraClub (cifra pronta)](#modo-cifraclub-cifra-pronta)
  - [Montagem manual](#montagem-manual)
  - [Teclas rápidas](#teclas-rápidas)
  - [Personalização](#personalização)
- [⌨️ Atalhos de teclado](#️-atalhos-de-teclado)
- [🎵 Modos de execução](#-modos-de-execução)
- [🎹 Acordes disponíveis](#-acordes-disponíveis)
- [✏️ Editor de acorde personalizado](#️-editor-de-acorde-personalizado)
- [📤 Exportação e compartilhamento](#-exportação-e-compartilhamento)
- [💾 Salvamento e projetos](#-salvamento-e-projetos)
- [📦 Dataset de samples](#-dataset-de-samples)
- [📁 Estrutura do projeto](#-estrutura-do-projeto)
- [🔧 Requisitos técnicos](#-requisitos-técnicos)
- [🐛 Problemas conhecidos](#-problemas-conhecidos)
- [🚀 Roadmap](#-roadmap)
- [🙏 Créditos](#-créditos)
- [📄 Licença](#-licença)

---

## 🎯 **O que é?**

O **Violão Compositor Sertanejo Pro** é uma aplicação web que simula um violão digital completo com foco em **composição e acompanhamento musical**. Diferente de aplicativos tradicionais que exigem conhecimento técnico, esta ferramenta foi projetada para ser usada por **qualquer pessoa**, independentemente do nível de experiência musical.

### ✨ **Diferenciais:**

- 🚀 **100% offline** — Funciona sem internet após carregar os samples (arquivos de áudio)
- 🎵 **Sons reais** — Utiliza samples de violão acústico profissional do dataset Kaggle
- 📝 **Modo CifraClub** — Cole cifras copiadas da internet e ouça imediatamente
- 🎤 **Karaokê integrado** — Acorde gigante exibido na tela para acompanhar cantando
- 🎸 **Mini-braço visual** — Diagrama de acordes no estilo CifraClub mostrando a posição exata dos dedos
- 🖱️ **Zero configuração** — Abra o arquivo, carregue os samples uma vez, e comece a usar
- 💾 **Persistência local** — Projetos e acordes personalizados salvos no navegador

---

## 👥 **Para quem é?**

| Perfil | Como esta ferramenta ajuda |
|---|---|
| 🎤 **Cantor** | Cole a cifra da música → Dê Play → Cante junto vendo o acorde gigante na tela |
| 🎸 **Violonista iniciante** | Veja o diagrama do acorde → Aprenda visualmente onde colocar os dedos |
| 🎓 **Músico intermediário** | Monte progressões → Teste diferentes ritmos e modos de execução |
| 📝 **Compositor** | Crie músicas completas → Exporte a cifra formatada → Compartilhe |
| 🎵 **Produtor musical** | Use como base harmônica de referência para produções |
| 👶 **Iniciante total** | Clique nos acordes → Ouça como soam → Aprenda sem teoria |

> 💡 **Zero conhecimento de teoria musical é necessário para começar!**

---

## ⚡ **Funcionalidades**

### 🎵 **Núcleo Musical**
- ✅ **36 samples** de violão acústico real com articulações profissionais
- ✅ **80+ acordes** pré-configurados (maiores, menores, com sétima, nona, suspensos, diminutos)
- ✅ **5 modos de execução:** Batida Sertaneja, Dedilhado Suave, Batida Cheia, Fingerstyle, Palm Mute
- ✅ **Editor de acordes personalizados** — Crie e salve seus próprios acordes
- ✅ **Piano Roll visual** — Timeline com blocos coloridos representando cada acorde
- ✅ **Controle de BPM** — Ajuste a velocidade de 40 a 220 batidas por minuto
- ✅ **Compasso configurável** — 4/4, 3/4 ou 6/8
- ✅ **Loop ativável** — Reprodução contínua da progressão

### 📝 **Modo CifraClub** (🆕 v2.3.0)
- ✅ **Cole cifras** diretamente do CifraClub, Cifras.com.br, Letras.mus.br e outros sites
- ✅ **Parser inteligente** que reconhece automaticamente: `C, Am, G7, F#m, Bb, C7M, C9, Cdim, Csus4...`
- ✅ **Atalho Ctrl+V** para colar cifras rapidamente sem usar o mouse
- ✅ **Conversão automática** do texto da cifra para a grade de reprodução

### 🎤 **Karaokê** (🆕 v2.3.0)
- ✅ **Acorde gigante** exibido no centro da tela durante a reprodução
- ✅ **Ideal para cantar junto** — mantenha o foco na melodia enquanto o acorde aparece
- ✅ **Fade out suave** — O acorde desaparece gradualmente, sem piscar

### 🎸 **Recursos Visuais**
- ✅ **Mini-braço CifraClub** — Diagrama flutuante que mostra a posição exata dos dedos no braço do violão
- ✅ **Detecção automática de pestana** (barre) — Exibida como barra horizontal no diagrama
- ✅ **Cordas soltas** — Círculo vazio (○)
- ✅ **Cordas mudas** — X vermelho (✕)
- ✅ **Destaque durante playback** — O bloco do acorde atual brilha e aumenta
- ✅ **Teclas do piano acendem** — Feedback visual das notas que estão soando

### 💾 **Gerenciamento de Dados**
- ✅ **Salvar/Carregar projetos** — Armazene suas progressões com nome personalizado
- ✅ **Exportar cifra** — Download automático como arquivo `.txt` formatado
- ✅ **Copiar progressão** — Para área de transferência com um clique
- ✅ **Acordes personalizados** — Persistidos no `localStorage` do navegador

---

## 🚀 **Como usar**

### **Primeiro acesso**

> ⚠️ **Importante:** O som do violão não funciona sem os samples. Siga este passo apenas na primeira vez.

1. **Abra o arquivo** `index.html` no seu navegador (Chrome recomendado)
2. **Clique em "📁 Carregar Samples"** na barra de ferramentas superior
3. **Selecione a pasta raiz** que contém as 42 subpastas do dataset (veja [Dataset de samples](#-dataset-de-samples))
4. **Aguarde o carregamento** — A barra de progresso mostrará o status
5. ✅ Quando o indicador ficar verde ("Samples Prontos!"), o violão está funcionando

> 💡 **Dica:** Os samples ficam armazenados na memória RAM. Se você recarregar a página (F5), precisará carregá-los novamente (leva 5-10 segundos).

---

### **Modo CifraClub (cifra pronta)**

**O jeito mais rápido de usar — ideal para cantores e iniciantes:**

1. **Copie uma cifra** de qualquer site (CifraClub, Cifras.com.br, etc.)
   ```
   Exemplo:
   C          G           Am         F
   Hoje eu quero te amar sem parar...
   
   Dm         G7          C
   E sentir o teu calor...
   ```

2. **Cole no campo** "Modo CifraClub" (painel esquerdo)
   - Atalho: Pressione `Ctrl+V` em qualquer lugar da página

3. **Clique em "🔄 Converter para Grade"**

4. **Clique em "▶ Play"** e cante junto!

> 🎤 O acorde atual aparece **gigante no centro da tela** para você acompanhar.

---

### **Montagem manual**

**Para quem quer criar sua própria progressão:**

1. **Explore as categorias** de acordes no painel esquerdo
   - Clique no nome da categoria (ex: "🎵 Maiores") para expandir/recolher

2. **Selecione um acorde:**
   - **Clique simples** = Seleciona o acorde (aparece no mini-braço)
   - **Duplo-clique** = Adiciona o acorde à grade de reprodução

3. **Monte a sequência** adicionando vários acordes

4. **Ajuste as configurações:**
   - **BPM:** Velocidade da reprodução
   - **Compasso:** 4/4 (padrão), 3/4 (valsa), 6/8 (xote)
   - **Modo:** Batida, Dedilhado, Fingerstyle, Palm Mute

5. **Clique em "▶ Play"** para ouvir

---

### **Teclas rápidas**

**Para montagem ultra-rápida usando apenas o teclado:**

| Tecla | Acorde |
|---|---|
| `1` | C (Dó Maior) |
| `2` | G (Sol Maior) |
| `3` | D (Ré Maior) |
| `4` | A (Lá Maior) |
| `5` | E (Mi Maior) |
| `6` | F (Fá Maior) |
| `Q` | Am (Lá Menor) |
| `W` | Em (Mi Menor) |
| `E` | Dm (Ré Menor) |
| `R` | Cm (Dó Menor) |
| `T` | G7 (Sol com Sétima) |

> Cada tecla **seleciona E adiciona** o acorde à grade automaticamente!

---

### **Personalização**

#### Criar um acorde personalizado:
1. Na seção **"✏️ Editor de Acorde Personalizado"** (painel esquerdo)
2. **Ajuste cada corda** individualmente:
   - `0` = Corda solta
   - `1-12` = Pressionar no traste correspondente
   - `-1` = Corda não toca (X)
3. O **preview** mostra qual nota musical cada corda está produzindo
4. Clique em **"▶ Testar"** para ouvir como ficou
5. Dê um **nome** ao acorde (ex: "MeuC7M")
6. Clique em **"💾 Salvar"**
7. O acorde aparecerá como uma **tag laranja** abaixo do editor

#### Usar o acorde personalizado:
- Clique na tag para selecioná-lo
- Duplo-clique para adicioná-lo à grade
- Ele funciona exatamente como os acordes pré-configurados

---

## ⌨️ **Atalhos de teclado**

| Tecla | Ação | Contexto |
|---|---|---|
| `Espaço` | Play / Pause | Qualquer lugar (exceto inputs) |
| `Delete` | Limpar toda a grade | Qualquer lugar (exceto inputs) |
| `Ctrl + Z` | Desfazer último acorde | Qualquer lugar (exceto inputs) |
| `Ctrl + V` | Colar cifra no campo CifraClub | Qualquer lugar |
| `Escape` | Fechar modais e popups | Qualquer lugar |
| `1` a `6` | Acordes maiores (C, G, D, A, E, F) | Qualquer lugar (exceto inputs) |
| `Q` a `T` | Acordes menores/sétima | Qualquer lugar (exceto inputs) |

---

## 🎵 **Modos de execução**

Cada modo usa uma **articulação diferente** do dataset, resultando em timbres e estilos distintos:

| Modo | Som | Articulação | Ideal para |
|---|---|---|---|
| 🎤 **Batida Sertaneja** | Rasqueado brilhante com palheta | `spn` — Sustain Palheta Normal | Sertanejo, MPB, Pop rock |
| 🤚 **Dedilhado Suave** | Toque suave P-I-M-A-M-I | `sfn` — Sustain Dedo Normal | Baladas, Canções românticas |
| 🔥 **Batida Cheia** | Rasqueado forte e encorpado | `spf` — Sustain Palheta Forte | Refrões, Country, Rock |
| 🎸 **Fingerstyle** | Padrão alternado dos dedos | `sfm` — Sustain Dedo Médio | Solos, Fingerstyle, Clássico |
| 🔇 **Palm Mute** | Cordas abafadas, percussivo | `npm` — Natural Palheta Médio | Reggae, Ska, Efeito rítmico |

> 💡 **Dica:** Alterne entre modos para dar dinâmica à sua música! Use "Dedilhado Suave" nos versos e "Batida Cheia" nos refrões.

---

## 🎹 **Acordes disponíveis**

### 🎵 Maiores (12 acordes)
`C` `C#` `D` `D#` `E` `F` `F#` `G` `G#` `A` `A#` `B`

### 🌙 Menores (12 acordes)
`Cm` `C#m` `Dm` `D#m` `Em` `Fm` `F#m` `Gm` `G#m` `Am` `A#m` `Bm`

### 7️⃣ Com Sétima Dominante (7 acordes)
`C7` `D7` `E7` `F7` `G7` `A7` `B7`

### ✨ Com Sétima Maior (7 acordes)
`C7M` `D7M` `E7M` `F7M` `G7M` `A7M` `B7M`

### 🎪 Suspensos (8 acordes)
`Csus2` `Dsus2` `Esus2` `Csus4` `Dsus4` `Esus4` `Gsus4` `Asus4`

### 💀 Diminutos (7 acordes)
`Cdim` `Ddim` `Edim` `Fdim` `Gdim` `Adim` `Bdim`

### 🎸 Nonas e Adicionadas (6 acordes)
`C9` `D9` `G9` `A9` `Cadd9` `Gadd9`

### 🤠 Sertanejos (4 acordes)
`C_sertanejo` `G_sertanejo` `D_sertanejo` `A_sertanejo`

### ✏️ Personalizados (ilimitado)
Crie quantos acordes quiser usando o editor!

---

## ✏️ **Editor de acorde personalizado**

O editor permite criar **qualquer acorde** personalizado, ajustando traste por traste:

### Como funciona:
```
Corda E6 (6ª) → Traste 0 = Solta (E2)
Corda A5 (5ª) → Traste 3 = Pressionada (C3)
Corda D4 (4ª) → Traste 2 = Pressionada (E3)
Corda G3 (3ª) → Traste 0 = Solta (G3)
Corda B2 (2ª) → Traste 1 = Pressionada (C4)
Corda E1 (1ª) → Traste 0 = Solta (E4)
```

### Valores possíveis:
| Valor | Significado | Visual no braço |
|---|---|---|
| `-1` | Corda não toca | ✕ Vermelho |
| `0` | Corda solta | ○ Círculo vazio |
| `1` a `12` | Pressionar no traste | ● Bolinha preta |

### Recursos:
- ✅ **Preview em tempo real** — Veja qual nota cada corda está produzindo
- ✅ **Botão Testar** — Ouça o acorde antes de salvar
- ✅ **Persistência** — Acordes salvos permanecem após fechar o navegador
- ✅ **Integração total** — Use seus acordes na grade, exportação, etc.

---

## 📤 **Exportação e compartilhamento**

### Exportar Cifra (.txt)
1. Monte sua progressão na grade
2. Clique em **"📝 Exportar Cifra"**
3. Um arquivo `.txt` será baixado automaticamente com:
   - Cabeçalho com data, BPM e compasso
   - Acordes organizados por compasso
   - Resumo com total de acordes

**Exemplo do arquivo gerado:**
```
🎸 Violão Compositor Sertanejo Pro
Data: 01/06/2026
BPM: 90 | Compasso: 4/4
Modo: batida_sertanejo
==================================================

| C        | G        | Am       | F        |
| C        | G        | F        | C        |

==================================================
Total: 8 acordes em 2 compassos
```

### Copiar Progressão
1. Clique em **"📋 Copiar Progressão"**
2. A sequência será copiada como texto puro: `C G Am F C G F C`
3. Cole em qualquer lugar (WhatsApp, Word, redes sociais)

---

## 💾 **Salvamento e projetos**

### Salvar Projeto
- Clique em **"💾 Salvar Projeto"**
- Dê um nome (ex: "Música da Festa Junina")
- O projeto salva: grade completa, BPM, compasso e modo de execução
- Dados armazenados no `localStorage` do navegador

### Carregar Projeto
- Clique em **"📂 Carregar Projeto"**
- Veja a lista de projetos salvos
- Digite o nome do projeto desejado
- Tudo será restaurado exatamente como estava

### O que é salvo:
| Item | Salvo? |
|---|---|
| Grade de acordes (sequência) | ✅ Sim |
| BPM configurado | ✅ Sim |
| Compasso (4/4, 3/4, 6/8) | ✅ Sim |
| Modo de execução | ✅ Sim |
| Acordes personalizados | ✅ Sim (separado) |
| Samples carregados | ❌ Não (recarregar) |

> ⚠️ **Atenção:** Projetos são salvos no navegador. Se limpar os dados do navegador, os projetos serão perdidos. Exporte como `.txt` para backup permanente.

---

## 📦 **Dataset de samples**

Este projeto utiliza o **Violão Acústico Dataset** com samples reais:

- **Fonte:** Kaggle — Acoustic Guitar Samples
- **Total de pastas:** 42 (A2 a G#5)
- **Arquivos por pasta:** 24 a 48 (varia por nota)
- **Formato:** `.wav`
- **Articulações:** Sustain/Natural × Palheta/Dedo/Unha × Normal/Médio/Leve/Forte
- **Nomenclatura:** `Nota-Número-Articulação.wav` (ex: `Gsharp3-15-spl.wav`)

### Estrutura de pastas esperada:
```
dataset/
├── A2/
├── A3/
├── A4/
├── Asharp2/      (A#2)
├── Asharp3/      (A#3)
├── Asharp4/      (A#4)
├── B2/
├── B3/
├── B4/
├── C3/
├── C4/
├── C5/
├── Csharp3/      (C#3)
├── Csharp4/      (C#4)
├── Csharp5/      (C#5)
├── D2/
├── D3/
├── D4/
├── D5/
├── Dsharp2/      (D#2)
├── Dsharp3/      (D#3)
├── Dsharp4/      (D#4)
├── Dsharp5/      (D#5)
├── E2/
├── E3/
├── E4/
├── E5/
├── F2/
├── F3/
├── F4/
├── F5/
├── Fsharp2/      (F#2)
├── Fsharp3/      (F#3)
├── Fsharp4/      (F#4)
├── Fsharp5/      (F#5)
├── G2/
├── G3/
├── G4/
├── G5/
├── Gsharp2/      (G#2)
├── Gsharp3/      (G#3)
├── Gsharp4/      (G#4)
└── Gsharp5/      (G#5)
```

### Como obter o dataset:
1. Acesse o [Kaggle — Acoustic Guitar Samples](https://www.kaggle.com/)
2. Faça o download do dataset completo
3. Extraia mantendo a estrutura de 42 pastas
4. Ao carregar no app, selecione a **pasta raiz** que contém as 42 subpastas

> 💡 O dataset **não está incluso** neste repositório devido ao tamanho (~200MB). Você precisa baixá-lo separadamente.

---

## 📁 **Estrutura do projeto**

```
violao-compositor-sertanejo/
│
├── index.html          ← Aplicação completa (HTML + CSS + JavaScript)
│                         Arquivo único e autossuficiente
│
├── README.md           ← Documentação completa (este arquivo)
│
└── samples/            ← Pasta com o dataset de áudio
    ├── A2/                  (não incluso no repositório)
    ├── A3/                  (baixar separadamente)
    ├── ...                  do Kaggle)
    └── Gsharp5/
```

> ⚠️ **Importante:** O arquivo `index.html` é **completamente autossuficiente**. Ele contém todo o HTML, CSS e JavaScript necessários em um único arquivo. Não requer:
> - ❌ Servidor web (Apache, Nginx)
> - ❌ Node.js ou npm
> - ❌ Build ou compilação
> - ❌ Instalação de dependências
> - ❌ Conexão com internet (após baixar os samples)

---

## 🔧 **Requisitos técnicos**

| Requisito | Mínimo | Recomendado |
|---|---|---|
| **Navegador** | Chrome 90+, Edge 90+, Firefox 88+, Safari 15+ | Chrome 120+ |
| **Memória RAM** | 2 GB | 4 GB+ |
| **Armazenamento** | 200 MB (para o dataset) | 500 MB |
| **Internet** | Apenas para baixar o dataset | — |
| **Sistema Operacional** | Windows 10+, macOS 11+, Linux | Qualquer SO moderno |
| **Placa de som** | Integrada | Qualquer |
| **Resolução** | 1024×768 | 1366×768+ |

### Compatibilidade:
| Navegador | Status |
|---|---|
| Google Chrome | ✅ Totalmente compatível |
| Microsoft Edge | ✅ Totalmente compatível |
| Mozilla Firefox | ✅ Totalmente compatível |
| Safari | ✅ Compatível (macOS/iOS) |
| Opera | ✅ Compatível |
| Internet Explorer | ❌ Não suportado |

---

## 🐛 **Problemas conhecidos**

| Problema | Impacto | Status | Solução/Contorno |
|---|---|---|---|
| Samples precisam ser recarregados ao atualizar a página (F5) | Baixo | ✅ Comportamento esperado | Recarregar os samples (5-10 segundos) |
| Som repetitivo em acordes consecutivos iguais (ex: C, C, C, C) | Baixo | ⚠️ Melhoria planejada | Alternar acordes ou usar round-robin (futuro) |
| Sem suporte para navegadores muito antigos | Médio | ✅ Requisito documentado | Atualizar para Chrome/Edge/Firefox |
| Mobile: layout pode ficar apertado em telas pequenas | Médio | ⚠️ Em melhoria | Usar em tablet ou desktop para melhor experiência |
| Cifras com formatação muito irregular podem não ser parseadas | Baixo | ✅ Comportamento esperado | Ajustar a cifra para um formato mais limpo |

---

## 🚀 **Roadmap**

### 🟢 Curto prazo (próximas semanas)
- [ ] **Round-robin** nos samples — Variação natural entre takes para evitar repetição
- [ ] **Seletor de duração** do acorde na cifra (1 compasso, meio compasso, 1 tempo)
- [ ] **Scroll automático** da grade durante o playback
- [ ] **Indicador de compasso** no cursor de reprodução

### 🟡 Médio prazo (próximos meses)
- [ ] **Gravação de áudio** — Exportar a progressão como arquivo `.wav` ou `.mp3`
- [ ] **Mais padrões rítmicos** — Xote, Baião, Samba, Reggae, Rock, Pop
- [ ] **Compartilhamento via link** — Gerar URL com a progressão codificada
- [ ] **Afinações alternativas** — Drop D, Open G, DADGAD, Meio-tom abaixo
- [ ] **Metrônomo visual** integrado ao playback

### 🔴 Longo prazo (visão futura)
- [ ] **Modo colaborativo** — Múltiplos usuários editando a mesma progressão em tempo real
- [ ] **Sugestão inteligente** — IA para sugerir acordes baseada no estilo musical
- [ ] **Banco de cifras** — Comunidade compartilhando progressões
- [ ] **App mobile nativo** — Versão para Android e iOS
- [ ] **Suporte a outros instrumentos** — Piano, Cavaquinho, Ukulele

---

## 🙏 **Créditos**

### 💻 Desenvolvimento
**Violão Compositor Sertanejo Pro** — Ferramenta open-source criada para democratizar a composição musical.

### 🎵 Dataset de Áudio
- **Kaggle — Acoustic Guitar Samples Dataset**
- Samples de violão acústico profissional com múltiplas articulações
- 42 notas, ~1000 arquivos de áudio, formato WAV

### 🎨 Inspiração
- **CifraClub** — Referência para o formato de diagramas de acordes no braço do violão
- **FL Studio / Ableton Live** — Inspiração para a interface Piano Roll
- **Ultimate Guitar** — Referência para a biblioteca de acordes

### 🛠️ Tecnologias utilizadas
- **HTML5** — Estrutura da aplicação
- **CSS3** — Estilização e design responsivo
- **JavaScript (ES6+)** — Toda a lógica do aplicativo
- **Web Audio API** — Engine de áudio e processamento sonoro
- **localStorage** — Persistência de dados no navegador

---

## 📄 **Licença**

### Código-fonte
Este projeto é distribuído sob a licença **MIT**.

```
MIT License

Copyright (c) 2026 Violão Compositor Sertanejo Pro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

### Dataset de Áudio
Os samples de áudio do dataset Kaggle possuem **licença própria**. Consulte os termos do dataset original no Kaggle para uso comercial ou redistribuição.

---

## 🎸 **Comece agora!**

1. **Baixe** o arquivo `index.html`
2. **Obtenha** o dataset de samples do Kaggle
3. **Abra** o `index.html` no seu navegador
4. **Carregue** os samples uma vez
5. **Comece a compor!** 🎵

---

**Feito com 🎸 para músicos, cantores, compositores e todos que amam música.**

---

*"A música é a linguagem universal da humanidade." — Henry Wadsworth Longfellow*
