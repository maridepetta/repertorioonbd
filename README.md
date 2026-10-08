# Repertório de Onboarding

Apresentações (PPT), planilhas (XLSX) e documentos (PDF) do time de onboarding.

## Estrutura

| Pasta | Conteúdo |
|---|---|
| `01-boas-vindas/` | Apresentação institucional e boas-vindas |
| `02-cultura-e-processos/` | Cultura, políticas e processos internos |
| `03-ferramentas/` | Guias das ferramentas usadas no dia a dia |
| `04-treinamentos/` | Treinamentos por área ou função |
| `05-modelos/` | Templates na identidade laranja e preto |

## Modelos prontos

| Arquivo | O que é |
|---|---|
| `05-modelos/template-apresentacao.pptx` | Apresentação com capa, agenda, divisor de seção, valores, números, linha do tempo e encerramento. Os layouts ficam em *Página Inicial → Layout* |
| `05-modelos/template-checklist-onboarding.xlsx` | Checklist com status em lista suspensa, % de progresso automático e aba de contatos |

**Para criar um material novo:** copie o template, renomeie seguindo o padrão abaixo e salve na pasta certa. Não edite o template original.

## Identidade visual

| Cor | Hex | Uso |
|---|---|---|
| Laranja | `#F26A1B` | Destaques, números, divisores de seção |
| Preto | `#111111` | Capas, encerramento, títulos |
| Cinza claro | `#F3F3F3` | Fundo de cards |
| Branco | `#FFFFFF` | Fundo dos slides de conteúdo |

- Texto **preto** sobre laranja. Evite branco sobre laranja: o contraste é baixo e fica difícil de ler.
- Fontes: **Arial** nos títulos e **Calibri** no texto.

## Como adicionar materiais

**Pelo navegador (sem instalar nada):** entre na pasta → *Add file* → *Upload files* → arraste os arquivos → *Commit changes*.

**Pela linha de comando:**
```bash
git lfs install          # uma vez por máquina
git add 01-boas-vindas/apresentacao.pptx
git commit -m "Adiciona apresentação de boas-vindas"
git push
```

## Regras

- **Nomes de arquivo:** `tema-descricao-AAAA-MM.ext`, sem espaços e sem acento (ex.: `cultura-valores-2026-10.pptx`).
- **Não crie cópias** como `final_v2_AGORA_VAI.pptx`: substitua o arquivo. O histórico do Git guarda as versões anteriores.
- **Avise antes de editar** um arquivo que outra pessoa está mexendo. Não dá pra mesclar duas versões de um PPT.
- **Limite de 100 MB por arquivo.** Vídeos grandes devem ficar no Drive/YouTube, com o link aqui.
- **Nada de dados pessoais** de colaboradores ou pacientes nos materiais.
