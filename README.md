<div align="center">

<img src="https://img.shields.io/badge/Darcy%20CV-Gerador%20de%20Curr%C3%ADculo-2F5FFF?style=for-the-badge&logoColor=white" alt="Darcy CV"/>

**Gerador de currículo gratuito para jovem aprendiz, estágio e primeiro emprego.**  
Monte, visualize em tempo real e baixe em PDF — direto no navegador, sem cadastro.

[![Status](https://img.shields.io/badge/status-ativo-16C784?style=flat-square)](https://github.com/projetodarcytech-art/DarcyCV)
[![HTML](https://img.shields.io/badge/HTML5-semântico-E34F26?style=flat-square&logo=html5&logoColor=white)](.)
[![CSS](https://img.shields.io/badge/CSS3-puro-1572B6?style=flat-square&logo=css3&logoColor=white)](.)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](.)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue?style=flat-square)](./LICENSE)

[🚀 Demo ao vivo](https://projetodarcytech-art.github.io/DarcyCV) · [🐛 Reportar bug](https://github.com/projetodarcytech-art/DarcyCV/issues) · [💡 Sugerir melhoria](https://github.com/projetodarcytech-art/DarcyCV/issues)

</div>

---

## Sobre o projeto

O **Darcy CV** é uma ferramenta web para quem está em busca do primeiro emprego. Em vez de exigir experiência profissional prévia, o gerador valoriza formação escolar, cursos complementares, idiomas e habilidades — tudo que um jovem aprendiz realmente tem para oferecer.

Você preenche os campos, a pré-visualização do currículo se atualiza letra a letra, e quando estiver pronto é só baixar em PDF. Nenhum dado sai do seu navegador.

> *"Seu futuro começa aqui."*

---

## Funcionalidades

- **Pré-visualização em tempo real** — o modelo se atualiza a cada campo preenchido, sem precisar clicar em "gerar"
- **Foto de perfil opcional** — envie uma imagem ou use as iniciais geradas automaticamente
- **Seções específicas para iniciantes** — escola, cursos, idiomas e habilidades em vez de "cargos anteriores"
- **Experiência profissional com repeater** — adicione quantas experiências quiser; cada uma aparece como card na pré-visualização
- **Cursos e certificações** — repeater dedicado para SENAI, cursos online, workshops etc.
- **Idiomas com nível** — Básico, Intermediário, Avançado ou Fluente
- **Tags de competências** — adicione habilidades técnicas como Pacote Office, CRM, Excel
- **Download em PDF** — exporta via impressão do navegador, sem instalar nada
- **100% gratuito e sem conta** — sem cadastro, sem plano pago, sem marca d'água
- **Dados só no navegador** — nenhuma informação é enviada a servidores
- **Layout responsivo** — funciona em desktop, tablet e celular
- **Acessível** — foco visível, `aria-label` nos botões, semântica HTML correta
- **Respeita `prefers-reduced-motion`** — animações desativadas para quem prefere

---

## Tecnologias

| Camada | Tecnologia |
|---|---|
| Estrutura | HTML5 semântico |
| Estilo | CSS3 — variáveis, Flexbox, Grid, `@media`, `@print` |
| Interatividade | JavaScript puro (ES6+), sem frameworks ou bibliotecas externas |
| Fontes | Google Fonts — Sora, Inter, JetBrains Mono |
| PDF | API nativa `window.print()` com regra `@media print` |
| Deploy | GitHub Pages |

---

## Como usar

### Visualizar localmente

Não precisa instalar nada. Basta:

```bash
git clone https://github.com/projetodarcytech-art/DarcyCV.git
cd DarcyCV
```

Abra o arquivo `index.html` no navegador. A extensão **Live Server** do VS Code também funciona.

### Preencher o currículo

1. **Cabeçalho** — nome, cidade, telefone, e-mail, LinkedIn e portfólio (opcionais)
2. **Foto** — envie uma imagem ou deixe as iniciais aparecerem automaticamente
3. **Objetivo** — cargo desejado e resumo profissional (já vem com um modelo de texto editável)
4. **Experiência** — opcional; preencha e clique em *Adicionar experiência*
5. **Formação** — escola, curso e status (cursando / concluído)
6. **Idiomas e habilidades** — adicione com Enter ou pelo botão
7. **Cursos e certificações** — SENAI, Coursera, workshops etc.
8. Clique em **Baixar em PDF** e salve o arquivo

---

## Estrutura do projeto

```
DarcyCV/
└── index.html   # aplicação completa (HTML + CSS + JS em um único arquivo)
```

Todo o código — estilos, lógica de formulário, pré-visualização e geração de PDF — está em `index.html`. Isso mantém o projeto simples de hospedar e de contribuir.

---

## Contribuindo

Contribuições são bem-vindas, especialmente melhorias de acessibilidade, novos templates e suporte a mais seções de currículo.

```bash
# 1. Fork o repositório
# 2. Crie uma branch descritiva
git checkout -b feat/nome-da-melhoria

# 3. Faça as alterações em index.html
# 4. Commit com mensagem clara
git commit -m "feat: adiciona campo para redes sociais"

# 5. Abra um Pull Request descrevendo o que mudou e por quê
```

Antes de abrir um PR, verifique:

- A pré-visualização ainda atualiza em tempo real
- O PDF gerado está correto (teste com `Ctrl+P` / `Cmd+P`)
- O layout continua responsivo em telas pequenas
- Nenhum dado pessoal de teste foi incluído no commit

---

## Roadmap

- [ ] Múltiplos templates de layout
- [ ] Campo de voluntariado / projetos pessoais
- [ ] Sugestão de texto por IA para o resumo profissional
- [ ] Paleta de cores personalizável
- [ ] Versão em inglês do formulário
- [ ] Integração com Atados para destacar experiências de voluntariado

---

## Licença

Distribuído sob a licença **MIT**. Veja [`LICENSE`](./LICENSE) para mais informações.

---

<div align="center">

Feito com 💙 pelo **Projeto Darcy Tech Art**

*Tecnologia com empatia — para quem está dando o primeiro passo.*

</div>
