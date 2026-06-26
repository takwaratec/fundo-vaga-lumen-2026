# AGENTS.md — Vaga Lúmen (FINEP Mais Inovação)

## Identidade

Proposta submetida ao edital **FINEP Mais Inovação — Rodada 2** (Subvenção Econômica), linhas 3 (Água e Esgoto) e 4 (Moradia e Espaços Públicos Sustentáveis).

**Projeto:** Vaga Lúmen — Laboratório Itinerante de Permacultura, Saneamento Descentralizado e Moradia Modular Sustentável.

**Grupo proponente:** ECOSALA — Núcleo Ribeirão Preto / Campinas.

---

## Objetivo do Agente

Ao ser acionado neste repositório, seu papel é:

1. **Estruturar a proposta FINEP** — manter documentos alinhados ao regulamento
2. **Organizar evidências técnicas** — TRL, artigos científicos, currículos da equipe
3. **Preparar anexos e formulários** — declarações, cartas de anuência, planilhas
4. **Acompanhar check-list de submissão** — itens pendentes e resolvidos
5. **Produzir documentação complementar** — memoriais, relatórios, bibliografia

---

## Estrutura do Repositório

```
📄 proposta-final-vaga-lumen.md            → Proposta formatada para submissão
📄 regulamento-finep-mais-inovacao.md       → Regulamento oficial transcrito (14p)
📄 plano-correcao-regulamento.md            → Falhas identificadas vs. regulamento
📄 reavaliacao-trl-evidencias.md            → TRL com evidências científicas (DOIs)
📄 compositos-alternativos-embarcacao.md     → Técnicas construtivas
📄 analise-lacunas-honesta.md               → TRL real de cada subsistema
📄 bibliografia-abnt.md                     → Referências em formato ABNT
📄 curatoria-imagens-andre.md               → Curadoria das imagens de André Blanco
📄 referencias-cientificas.md               → Artigos sobre captação de água
📄 relatorio-alteracoes.md                  → Histórico de mudanças
📂 docs/
├── projeto-vaga-lumen-andre-blanco.md      → Projeto original (convertido de .docx)
├── proposta-financiadores-andre-blanco.md  → Proposta para financiadores
└── editais/                                → Outros editais de interesse
```

---

## Mapa de Atribuições — Atores do ECOSALA

| Ator | Papel | Tipo de contribuição |
|---|---|---|
| **André Blanco** | Arquiteto, Labiapa | Áudios WhatsApp, projetos construtivos, articulação FINEP/Fábrica Modelo |
| **Fabio Takwara** | Pesquisador autodidata, tecnologias sociais | Inserções manuais de documentos (Chapada, Holambra, PU Vegetal). O que está em chat/e-mail/áudio é delegado ao agente |
| **Gisele Vilela** | Pesquisadora Embrapa | Documentos técnicos, articulação institucional |
| **Marcos Paron** | Professor IFSP | Coordenação, ecoformação, articulação acadêmica |
| **Joaquim Sando** | Eng. Agrônomo, MST | Articulação territorial |
| **Daniela Maciel** | Pesquisadora Embrapa | Fundação gestora (reunião pendente) |
| **Murilo Miguel** | Coletivo Terra Viva | Operação de campo |
| **Demais membros** | ECOSALA | Fichas pessoais, contribuições documentais |

> **Fluxo:** Fabio faz inserções manuais de arquivos no repositório. Conteúdo de WhatsApp, e-mail e áudio é processado pelo agente e atribuído ao autor correspondente. Nunca atribuir a autoria de documentos a quem não os produziu.

---

## Ferramentas Disponíveis

| Ferramenta | Função | Status |
|---|---|---|
| **Pandoc** | DOCX/ODT → MD | ✅ |
| **PyMuPDF** (fitz) | Extração de texto de PDFs | ✅ |
| **python-docx** | Leitura/escrita DOCX | ✅ |
| **ffmpeg** (conda) | Conversão de áudio (opus → wav) | ✅ |
| **faster-whisper** | Transcrição de áudio | ✅ | via `conda run -n whisper_env` |
| **pdfplumber** | PDF tabular | ⏳ Pendente (rede) |

**Workaround áudio:** Gateway Telegram já transcreve automaticamente. Para áudios locais, ffmpeg disponível.

---

## Convenções para o Agente

### Documentos
- Converter originais (.docx, .odt, .pdf) para .md antes de versionar
- NUNCA commitar binários grandes — vão para TRIAGEM-BRUTA/
- NUNCA inflar TRL ou dados técnicos — exige-se honestidade absoluta
- Referências sempre com DOI verificado e formato ABNT

### Fluxo de trabalho
1. `git pull` — sincronizar com remoto
2. Fazer alterações
3. `git add <arquivos> && git commit -m "tipo: descrição" && git push`

### Regras críticas
- ❌ NUNCA fabricar citações de figuras públicas (cientistas, autores)
- ❌ NUNCA inflar TRL em propostas
- ❌ NUNCA citar documentos internos (prefixos LAB_, ENG_, RES_, SCI_, TAK_) como evidência — só artigos públicos com DOI
- ❌ NUNCA usar termos como "biosoberano" ou "protocolos disso/daquilo" em textos públicos — são metáforas internas
- ✅ Tecnologia Takwara = proposta TRL laboratorial, nunca como tecnologia aplicada em comunidades
- ✅ Usar paráfrase explícita quando não houver transcrição literal verificada
- ✅ Atribuir sempre com honestidade

---

## Repositórios Irmãos

| Repositório | Conteúdo | Público |
|---|---|---|
| `github.com/takwaratec/ECOSALA` | Coletivo de 11 membros — atas, projetos | Grupo de pesquisa |
| `github.com/takwaratec/plataforma-juventude-solidaria-2026` | Viveiro-Educador Terra Viva (MST) | MST Mário Lago |
| `github.com/takwaratec/Analises-e-escrita-cientifica` | Acervo científico — fichas, artigos, TRL | Acadêmico |

---

## Acervo Científico

👉 https://takwaratec.github.io/Analises-e-escrita-cientifica/

---

*AGENTS.md mantido pelo Hermes Agent · Tecnologia Takwara · 2026*
