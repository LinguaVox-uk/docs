<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Ditado por Voz com IA para Chrome" />
</p>

<h3 align="center">LinguaVox — Ditado por Voz com IA para Chrome · 21+ Idiomas · Transcrição em Tempo Real</h3>

<p align="center">
  Pressione o atalho · fale · solte · o texto aparece automaticamente em qualquer campo web<br>
  OpenAI Whisper · 21+ idiomas · 6 modos IA · Legendas ao vivo em reuniões · Sem chave de API
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licença-MIT-blue.svg" alt="Licença" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/site-linguavox-brightgreen" alt="Site" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Instalar%20Grátis-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/painel-abrir-orange" alt="Painel" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/versão-3.0.0-green" alt="Versão" /></a>
</p>

---

## O que é LinguaVox?

LinguaVox é uma extensão Chrome para ditado por voz e tradução com inteligência artificial. Pressione Ctrl+Espaço, fale, solte — o texto transcrito aparece imediatamente no campo ativo: chat, e-mail, formulário CRM, comentário no Jira, bloco no Notion. A extensão usa OpenAI Whisper para precisão de 95%+ e GPT-4o-mini para melhoria opcional do texto: correção gramatical, mudança de estilo, tradução.

Ao contrário da maioria das ferramentas de ditado, LinguaVox não exige uma chave API OpenAI pessoal. Usuários gratuitos recebem 20 solicitações por dia do pool compartilhado — sem nenhuma configuração. Usuários avançados e equipes podem conectar sua própria chave para uso ilimitado.

**v3.0 — Modo Reunião:** legendas traduzidas em tempo real para Google Meet, Zoom, Teams e qualquer videochamada baseada em navegador. O áudio da aba é capturado pela API Chrome → enviado ao Deepgram → legendas aparecem como sobreposição flutuante.

## Como Funciona

**Antes do LinguaVox:** abrir app separado → gravar → copiar → trocar de app → colar  
**Com LinguaVox:**

```
1. Clique em qualquer campo web (Slack, Gmail, Notion, Jira…)
2. Segure  Ctrl+Espaço  →  fale
3. Solte  →  texto aparece em ~3 segundos  ✓
```

Sem copiar-colar. Sem trocar de app. Em qualquer site.

## Onde Funciona

| Plataforma | Status | Notas |
|------------|--------|-------|
| Slack (navegador) | ✅ | Atalho no nível do navegador contorna captura de teclas do Slack |
| Gmail | ✅ | Campos de composição e resposta |
| Notion | ✅ | Todos os blocos contenteditable |
| Jira | ✅ | Campos de issue, comentários, descrições |
| Asana | ✅ | Campos de tarefa e comentário |
| Salesforce | ✅ | Campos de entrada CRM |
| Qualquer `<input>` / `<textarea>` | ✅ | Universal |
| Qualquer `contenteditable` | ✅ | Compatível com React, Draft.js, Quill |
| Google Docs | ⚠️ | Limitado — editor canvas personalizado |

## Recursos Principais

- **Sem chave de API obrigatória** — 20 solicitações/dia gratuitas via pool compartilhado
- **Traga sua própria chave** — uso ilimitado ao custo OpenAI
- **Contas de organização** — pool de chaves compartilhadas, gerenciamento de membros, análise de uso
- **21+ idiomas** — transcrição + tradução em uma única etapa
- **6 modos de aprimoramento IA** — correção gramatical, estilo profissional, acadêmico, casual, criativo, polimento inteligente
- **Modo Reunião** — legendas em tempo real para qualquer áudio de aba via Deepgram
- **Privacidade total** — áudio de voz nunca armazenado
- **Menos de 3 segundos** — do áudio à inserção do texto
- **Precisão 95%+** — OpenAI Whisper

## Modos de Aprimoramento IA

| Modo | O que faz |
|------|----------|
| Polimento Inteligente | Corrigir gramática, melhorar clareza, preservar significado |
| Estilo Profissional | Tom de comunicação profissional e formal |
| Só Gramática | Corrigir gramática e ortografia apenas |
| Estilo Criativo | Escrita vívida e envolvente |
| Estilo Casual | Tom conversacional e amigável |
| Estilo Acadêmico | Linguagem acadêmica formal |

## Preços

| Plano | Solicitações/dia | Requisitos |
|-------|-----------------|-----------|
| Gratuito | 20 | Conta Google (login OAuth) |
| Traga sua chave | Ilimitadas | Conta Google + chave API OpenAI pessoal |
| Organização | Ilimitadas | Conta Google + chave API compartilhada da equipe |

## Perguntas Frequentes

**LinguaVox funciona no Slack?**  
Sim. O Slack intercepta eventos de teclado no nível da página. LinguaVox registra o atalho no nível do navegador via `chrome.commands.onCommand`, contornando a captura do Slack.

**Preciso de uma chave API OpenAI?**  
Não. Usuários gratuitos recebem 20 solicitações/dia do pool compartilhado. Adicione sua própria chave no painel para uso ilimitado.

**Minha voz é gravada ou armazenada?**  
Não. O áudio é processado em tempo real pelo Whisper e descartado imediatamente. Zero dados de voz retidos.

**Quais idiomas são suportados?**  
21+ idiomas: português, inglês, ucraniano, russo, espanhol, francês, alemão, japonês, coreano, chinês, árabe, italiano, polonês, holandês, turco, sueco, romeno, grego, filipino, urdu, punjabi e mais.

## Comunidade e Suporte

| | |
|--|--|
| 📺 YouTube | [Vídeos de demonstração e tutoriais](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Canal da Comunidade LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Junte-se a linguavox.slack.com](https://linguavox.slack.com) |

## Vídeos de Demonstração

| Caso de uso | Assistir |
|-------------|---------|
| Gmail — ditando e-mails por voz | [▶ Assistir](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — mensagens de voz | [▶ Assistir](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — ditado por voz | [▶ Assistir](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — escrevendo posts por voz | [▶ Assistir](https://youtube.com/watch?v=3WX9EmYNYjk) |
| Modo Reunião — legendas em tempo real | [▶ Assistir](https://youtube.com/watch?v=agcMJVPKlxE) |

## Instalação

**Opção A — Chrome Web Store (recomendado):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — clique em "Adicionar ao Chrome"
2. Clique no ícone LinguaVox → "Entrar com Google"
3. Pressione Ctrl+Espaço em qualquer lugar e comece a falar

**Opção B — Instalação manual (ZIP):**
1. Baixe `linguavox-3.0.0.zip` de [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Extraia para uma pasta
3. Chrome → `chrome://extensions` → ative "Modo desenvolvedor" → "Carregar sem compactação" → selecione a pasta

## Links

| | |
|--|--|
| 🌐 Site | https://linguavox.uk |
| 📊 Painel | https://linguavox.uk/login |
| 🔒 Política de Privacidade | https://linguavox.uk/privacy/ |
| 🤖 Docs IA (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Suporte | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licença

MIT — consulte [LICENSE](LICENSE)