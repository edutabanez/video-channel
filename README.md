# Video Channel — Youcast Channel in a Box

Repositório oficial para desenvolvimento do vídeo comercial em motion design da **Youcast: Channel in a Box**.

---

## 📋 Contexto do Projeto

Este projeto tem como objetivo criar um vídeo comercial de 30 segundos, totalmente focado em narrativa visual e motion design, sem necessidade de áudio.

### Especificações Técnicas
- **Formato:** MP4 / H.264 (`yuv420p`), Full HD (1920 × 1080), 16:9 widescreen.
- **Duração:** Exatamente 30 segundos / 30 fps / 900 frames.
- **Áudio:** 100% silencioso (sem locução, música, efeitos sonoros ou faixa de áudio).
- **Tecnologia:** React + Remotion (animação baseada em frames determinísticos).
- **Identidade Visual:** Youcast (Preto/Grafite, Branco e Amarelo Youcast `#F3D34A`).
- **Estrutura de Cenas:** 5 cenas conectadas (Conteúdo → Canal na Nuvem → Distribuição Multitelas → Monetização SSAI → Encerramento com Marca).

O roteiro detalhado cena a cena e as diretrizes completas de motion design estão documentados em:
👉 **[`docs/PROMPT_LOVABLE.md`](docs/PROMPT_LOVABLE.md)**

---

## 🤖 Como Compartilhar com o ChatGPT

Como este repositório é **público**, você pode compartilhar o código e as especificações diretamente com o ChatGPT das seguintes formas:

### 1. Compartilhamento via Link Direto
Envie o link público do repositório ou de arquivos específicos para o ChatGPT:
- **Repositório:** `https://github.com/edutabanez/video-channel`
- **Roteiro e especificações:** `https://raw.githubusercontent.com/edutabanez/video-channel/main/docs/PROMPT_LOVABLE.md`

### 2. Prompt Recomendado para Iniciar Conversa no ChatGPT
Copie e cole a mensagem abaixo no ChatGPT para contextualizá-lo rapidamente:

```text
Olá! Estou desenvolvendo um vídeo comercial de 30s em Remotion/React para o produto "Youcast Channel in a Box".
O repositório do projeto é público: https://github.com/edutabanez/video-channel

Por favor, revise o arquivo docs/PROMPT_LOVABLE.md e me ajude com:
1. Revisão e criação de componentes Remotion para cada uma das 5 cenas.
2. Animações e interpolações com useCurrentFrame() e spring() sem uso de áudio.
3. Boas práticas de motion graphics para alta legibilidade e contraste.
```

### 3. Compartilhando Trechos de Código
Caso precise de suporte para uma cena específica, copie o arquivo correspondente (ex: `src/scenes/Scene1.tsx`) e envie com o seguinte formato:

```text
Aqui está a Cena [N] do meu vídeo em Remotion:
[Cole o código aqui]

Preciso melhorar [a transição / o timing / o destaque em amarelo] mantendo a duração exata dessa cena no roteiro.
```

---

## 📁 Estrutura do Repositório

```text
video-channel/
├── docs/
│   └── PROMPT_LOVABLE.md   # Roteiro completo, tempos e regras de produção
├── src/                    # Código fonte Remotion (cenas, componentes, root)
└── README.md               # Contexto e instruções de colaboração
```
