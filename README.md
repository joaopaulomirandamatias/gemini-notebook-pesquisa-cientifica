# Gemini Notebook para pesquisa científica: passo a passo (MirandasTech)

Manual em formato de slides (52) sobre o Gemini Notebook (o antigo NotebookLM, renomeado em 16/07/2026) para pós-graduação: começar (conta, página inicial, notebook e os três painéis), fontes (o que aceita e em que limite, «Adicionar fontes», URLs de editoras que falham, Descobrir fontes, Drive, seleção e rótulos), conversar com as fontes (perguntas boas para pesquisa, citações numeradas e o trecho, «Salvar como nota», estilos de conversa), Estúdio (Resumo em Áudio e em Vídeo, mapa mental, relatórios, cartões, teste, infográfico, apresentação, tabela de dados), seis fluxos de pesquisa (triagem de PDFs, leitura profunda IMRaD, matriz de síntese, aula, banca, ponte com o Zotero e os agentes), colaboração, limites, privacidade e ética, erros comuns, checklist, glossário com popovers e referências. Capturas reais e datadas (08/09/2026) da interface em português, feitas num notebook de exemplo com artigos de acesso aberto.

**Manual on-line:** https://notebook.mirandastech.com.br/ · **PDF:** https://notebook.mirandastech.com.br/manual.pdf

Manuais irmãos: **Metodologia** — https://metodologia.mirandastech.com.br/ · **Zotero** — https://manual.mirandastech.com.br/zotero/ · **Uso de IA na pesquisa** — https://manual.mirandastech.com.br/

| Pasta | O que há |
|---|---|
| `manual/` | deck HTML autônomo, PDF e fonte do artefato |
| `site/` | o que o servidor serve (`index.html`, `manual.pdf`) |
| `capturas/` | capturas reais, 08/09/2026, nomeadas por passo (e-mails e notebooks de terceiros borrados) |
| `modelos/prompts.md` | todos os prompts do manual (inventário, triagem, fichamento IMRaD, matriz de síntese, aula, banca) e a declaração de uso de IA |
| `modelos/estrutura_notebooks.md` | um notebook por etapa: o que entra, para quê, o que sai |
| `scripts/gerar_deck.py` | regenera HTML e PDF a partir do fonte |
| `Dockerfile` · `Caddyfile` · `railway.json` | deploy estático (Caddy) |
| `.github/workflows/verificar.yml` | CI: integridade do deck e capturas referenciadas |

## Os manuais juntos
Este manual é a camada de **leitura e síntese**: o corpus fechado pelo Zotero é lido no Gemini Notebook com o trecho ao alcance, e a matriz e as notas voltam para o Zotero e para o texto. Decisões de método ficam com o **Metodólogo** (repositório `metodologia-pesquisa-cientifica`), o uso de IA com o **Orientador** (`ia-na-pesquisa-cientifica`) e a biblioteca com o **Bibliotecário** (`zotero-pesquisa-cientifica`). O Gemini Notebook não tem API pública nem extensão oficial em setembro de 2026: a ponte é por arquivo (PDF para dentro; Docs e Sheets para fora).

## Como citar
MATIAS, J. P. M. *Gemini Notebook para pesquisa científica: passo a passo.* MirandasTech, v1.0, set. 2026. CC BY 4.0.

## Declaração de uso de IA
Escrito com assistência de IA (Claude, Anthropic) na estruturação, redação e automação das capturas. Nome do produto, limites por plano, tipos de fonte, recursos do Estúdio, política de privacidade e orientações universitárias conferidos nas fontes oficiais em 08/09/2026; os nomes de botões seguem a interface em português observada na mesma data. O autor responde integralmente pelo conteúdo. Gemini Notebook é um produto do Google; este manual não tem vínculo com a empresa.
