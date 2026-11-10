# Guia para escrever o TCC no formato relatório técnico

> **Orientações do professor Rodrigo Rebouças de Almeida para os seus orientandos.**
> Este material não é documento oficial da disciplina de TCC, do curso nem da UFPB.
> Quando houver diferença entre ele e a resolução de TCC, as normas do curso ou as
> orientações da coordenação da disciplina, valem as normas oficiais.

Material de apoio para os estudantes que eu oriento no Trabalho de Conclusão de Curso
no formato Artigo Tecnológico ou Relatório Técnico, previsto na resolução de TCC. Ele
descreve a estrutura do documento, o que cada seção precisa conter e os critérios que
eu uso para revisar cada versão do texto. Estudantes de outros orientadores podem usar
o material como referência, sabendo que cada orientador tem os próprios critérios.

Autor: Rodrigo Rebouças de Almeida, Departamento de Ciências Exatas (DCX), Centro de
Ciências Aplicadas e Educação, UFPB, Campus IV.

## Conteúdo do repositório

| Caminho | Conteúdo |
|---|---|
| [`guia/guia-tcc-relatorio-tecnico.pdf`](guia/guia-tcc-relatorio-tecnico.pdf) | O guia completo, em PDF. A versão em Word, para adaptação, está na mesma pasta. |
| [`criterios/criterios-tcc.md`](criterios/criterios-tcc.md) | Os critérios de revisão, num arquivo único. O guia, a skill do estudante e a revisão do orientador usam o mesmo conteúdo. |
| [`claude/tcc-aluno/`](claude/tcc-aluno/) | A skill de apoio ao estudante, para Claude, Codex e outras ferramentas que leem o formato SKILL.md. |
| [`claude/tcc-aluno.zip`](claude/tcc-aluno.zip) | A mesma skill empacotada, para enviar ao claude.ai. |
| [`outros-assistentes/instrucoes.md`](outros-assistentes/instrucoes.md) | As instruções da skill em texto corrido, para usar no ChatGPT, no Gemini ou em outro assistente. |

## O guia

Comece pelo [PDF](guia/guia-tcc-relatorio-tecnico.pdf). Leia as seções 2, 3 e 4 antes
de escrever e use o checklist da seção 10 antes de cada entrega. A seção 8 trata do uso
de ferramentas de IA, inclusive deste material.

## O assistente de apoio

O assistente ajuda em quatro situações: planejar objetivos e metodologia, revisar uma
seção, conferir o texto completo antes de entregar e conferir referências. Ele usa os
mesmos critérios que eu uso na revisão.

Ele não escreve o TCC por você. Não redige seções, não gera dados nem resultados e não
inventa referências. Também não substitui a avaliação do orientador. O uso do
assistente é uso de ferramenta de IA e precisa entrar na declaração de uso do seu TCC
(seção 8 do guia).

### Claude (claude.ai)

1. Baixe o arquivo [`claude/tcc-aluno.zip`](claude/tcc-aluno.zip).
2. No claude.ai, abra Configurações, depois Capacidades, e envie o arquivo na área de
   Skills.
3. Em uma conversa, peça ajuda com o TCC ou anexe o texto. A skill é ativada pelo
   assunto do pedido.

### Claude Code, Codex e outras ferramentas que leem SKILL.md

Copie a pasta `claude/tcc-aluno` para a pasta de skills da ferramenta:

| Ferramenta | Pasta |
|---|---|
| Claude Code | `~/.claude/skills/tcc-aluno` |
| Codex (CLI, extensão de IDE e ChatGPT desktop) | `~/.agents/skills/tcc-aluno` |
| Gemini CLI | `~/.gemini/skills/tcc-aluno` ou `~/.agents/skills/tcc-aluno` |

```bash
git clone https://github.com/rodrigor/guia-tcc.git
```

```bash
cp -R guia-tcc/claude/tcc-aluno ~/.agents/skills/
```

O Gemini CLI foi substituído pelo Antigravity CLI em junho de 2026, e as pastas podem
ser outras nas instalações novas. Confira a documentação da ferramenta que você usa.

### ChatGPT (navegador ou aplicativo)

No ChatGPT, crie um Projeto (ou um GPT personalizado, se o seu plano permitir):

1. Cole o conteúdo de [`outros-assistentes/instrucoes.md`](outros-assistentes/instrucoes.md)
   no campo de instruções.
2. Anexe como arquivos do projeto o [`criterios-tcc.md`](criterios/criterios-tcc.md) e o
   [PDF do guia](guia/guia-tcc-relatorio-tecnico.pdf).
3. Abra conversas dentro desse projeto para trabalhar no TCC.

### Gemini (navegador ou aplicativo)

No Gemini, crie um Gem:

1. Cole o conteúdo de [`outros-assistentes/instrucoes.md`](outros-assistentes/instrucoes.md)
   no campo de instruções do Gem.
2. Adicione como conhecimento o [`criterios-tcc.md`](criterios/criterios-tcc.md) e o
   [PDF do guia](guia/guia-tcc-relatorio-tecnico.pdf).
3. Use o Gem nas conversas sobre o TCC.

### Qualquer outro assistente

Comece a conversa colando o conteúdo de `instrucoes.md` e anexando o `criterios-tcc.md`
e o PDF do guia. Repita isso a cada conversa nova, porque assistentes sem projeto ou
instruções salvas não guardam as instruções.

## Licença

O guia, os critérios e as instruções estão sob a licença
[Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)](LICENSE). Você pode usar,
adaptar e redistribuir o material, inclusive em outras instituições, desde que cite a
autoria.
