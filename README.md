# CapiReps — Política de Privacidade

Página pública da política de privacidade do app **CapiReps** (Capivara
Studios), publicada no **GitHub Pages**.

Este repositório é a **fonte única** do texto publicado: o repositório do app
não guarda cópia nenhuma da política. Mudou o app → muda aqui.

- `index.html` — página completa (pt-BR/en, responsiva, autocontida, sem
  dependência externa)
- `privacy-policy.md` — a mesma política em Markdown (pt-BR), para colar no
  Console ou para leitura
- `.nojekyll` — evita o processamento do Jekyll no Pages

## Endereço publicado

`https://lasantos704.github.io/capireps-privacy/`

Essa é a URL usada no **Google Play Console** em **Conteúdo do app → Política
de privacidade**. Pages já está configurado (**Deploy from a branch** ·
`main` · `/ (root)`).

## Atualizar

1. Edite `index.html` **nos dois idiomas** (os blocos `<section id="pt">` e
   `<section id="en">` descrevem as mesmas coisas — manter paridade é regra).
2. Espelhe o texto em `privacy-policy.md`.
3. Atualize a data: `Atualizado em DD/MM/AAAA` no cabeçalho da página.
4. Commit e push. O Pages republica sozinho em ~1 minuto.

```bash
git add index.html privacy-policy.md README.md
git commit -m "docs: atualiza a política de privacidade"
git push
```

## O que a página precisa continuar cobrindo

Sempre que o app ganhar um recurso que toque dados, confira se estes pontos
continuam verdadeiros:

- **100% offline**: sem cadastro, login, servidor, analytics, rastreamento ou
  publicidade.
- **Dados armazenados**: treino (incluindo observações, check-in, duração
  adaptada, perfis de equipamento, metas por músculo, recordes, XP, conquistas,
  **missões pessoais e seus recibos**) e a seção **Saúde opcional** (pesos,
  circunferências, laudos de bioimpedância digitados, metas, catálogo de
  alimentos/receitas, refeições, bebidas, confirmação do dia). O celular **não
  mede** composição corporal e o app **não** conecta a aparelhos.
- **Canais de saída** — todos por ação sua, pelo seletor do sistema, e todos em
  texto claro: backup JSON, `.txt` de relatório de Saúde, **CSV do histórico**,
  **arquivo de plano** e **card PNG** de sessão. Dizer o que cada um contém e
  que Saúde não entra no CSV, no plano nem no card.
- **O que a importação substitui** e o aviso de que um backup antigo apaga as
  áreas que ele não traz.
- **Ciclo de vida dos arquivos temporários**: cópia de importação removida após
  a leitura, cópias de exportação vencidas em 24h, falha/cancelamento apagam a
  cópia recém-criada.
- **Lembretes locais e widget da tela inicial**: opcionais, desligados por
  padrão, dependentes da permissão do sistema, com texto de rótulo fixo (nada de
  rotina, observação ou dado de Saúde na tela bloqueada) e conteúdo do widget
  limpo ao desligar.
- **Exclusão**: **Apagar somente Saúde** (preserva treinos, XP, missões,
  equipamento e preferências) e **Apagar todos os dados**; exclusão é lógica,
  não forense, e cópias externas/backups do sistema não são revogados.
- **Sem criptografia própria nem bloqueio biométrico**; o aparelho é a
  responsabilidade de quem usa.
- **Crianças** e **contato**: `contato.capistudios@gmail.com`.

## Pré-visualizar localmente

```bash
npx serve .
```

Ou abra `index.html` diretamente no navegador.

## Contato

contato.capistudios@gmail.com
