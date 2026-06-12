# Morary — Companheiro Digital de Bem-Estar Emocional

> Landing page desenvolvida como projeto acadêmico da disciplina de Empreendedorismo, apresentando o Morary: uma extensão de navegador voltada ao cuidado emocional no cotidiano digital.

---

## Sobre o projeto

O **Morary** é um companheiro digital pensado para aparecer em momentos estratégicos do dia, convidando o usuário a fazer pequenas pausas de autocuidado — exercícios de respiração, escrita emocional, sons relaxantes e registro de humor. Não substitui terapia; cria espaços gentis de atenção emocional dentro da rotina.

Esta landing page apresenta o conceito, as funcionalidades, o público-alvo e a visão futura do projeto.

---

## Tecnologias utilizadas

- **HTML5** — estrutura semântica
- **Bootstrap 5.3** — sistema de grid responsivo e classes utilitárias de layout
- **CSS3 customizado** — identidade visual, animações e design tokens do projeto
- **Google Fonts** — Playfair Display (títulos) e DM Sans (corpo)
- **SVG inline** — ícones leves sem dependência externa

> Bootstrap carregado via CDN — sem necessidade de instalação ou ferramentas de build.

---

## Estrutura de arquivos

```
Morary_Projeto-de-Empreendedorismo/
├── index.html        # Estrutura da página com classes Bootstrap
├── style.css        # Identidade visual, animações e variáveis CSS
└── IMG/
    ├── Banner - Morary.png
    └── Companheiro Morary.png
```

---

## Seções da landing page

| Seção | Descrição |
|---|---|
| **Hero** | Apresentação do Morary com animação de flutuação e respiração |
| **Problema** | Por que pausas emocionais são necessárias no cotidiano digital |
| **Solução** | A proposta do Morary como extensão leve e não invasiva |
| **Como funciona** | Intervalos programados, horários críticos e atalho de teclado |
| **Funcionalidades** | Pausas guiadas, escrita emocional, reflexões e sons relaxantes |
| **Registro emocional** | Demo visual do sistema de acompanhamento de humor |
| **O companheiro** | Os estados do personagem digital e seu significado simbólico |
| **Público-alvo** | Estudantes, profissionais digitais e pessoas ansiosas |
| **Diferenciais** | O que torna o Morary diferente de outros apps de bem-estar |
| **Visão futura** | Funcionalidades planejadas para evoluções do projeto |

---

## Como visualizar localmente

Nenhuma instalação é necessária. Basta:

1. Clonar ou baixar o repositório
2. Abrir a pasta no **VSCode**
3. Usar a extensão **Live Server** (botão "Go Live" no canto inferior direito)

Ou simplesmente abrir o arquivo `index.html` diretamente no navegador.

---

## Como o Bootstrap foi aplicado

O Bootstrap 5 foi integrado via CDN e utilizado exclusivamente para estrutura e layout, preservando toda a identidade visual original no `styles.css`. As principais aplicações foram:

- **Grid responsivo** com `row` e `col-md-*` / `col-sm-*` substituindo grids CSS manuais
- **Flexbox utilitário** com `d-flex`, `align-items-center`, `justify-content-center`
- **Espaçamentos declarativos** com `p-4`, `mb-5`, `gap-3`, `mx-auto`
- **Bordas e arredondamentos** com `border`, `rounded-4`, `rounded-pill`, `rounded-circle`
- **Controle de ordem responsiva** com `order-md-1` e `order-md-2`
- **Utilitários de texto** com `text-center`, `text-uppercase`, `list-unstyled`

> O CSS customizado cuida das cores, tipografia, animações e variáveis do projeto. O Bootstrap cuida da estrutura.

---

## Repositório da versão anterior

Este projeto é uma evolução da versão original desenvolvida sem frameworks:

🔗 [Morary — versão HTML + CSS puro](https://github.com/SaraCastilhos/Morary---Companheiro-de-bem-estar-emocional)

---

## Autora

**Sara Castilhos**
Projeto acadêmico — Disciplina de Empreendedorismo
