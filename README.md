Este repositório contém **dois projetos web** que replicam o mesmo layout utilizando **HTML semântico** combinado com duas abordagens diferentes de CSS:

1. **Projeto 1 – Layout com Flexbox**
2. **Projeto 2 – Layout com CSS Grid + Flexbox**

  Estrutura dos Projetos

  Projeto 1: Flexbox
- Utiliza **Flexbox** para toda a estrutura do layout.
- A disposição dos elementos principais é feita com `display: flex`.
- Ideal para layouts lineares (em linha ou coluna).

  Projeto 2: CSS Grid + Flexbox
- Utiliza **CSS Grid** para estruturar o layout principal (colunas).
- Utiliza **Flexbox** para o conteúdo interno de seções, como artigos e seções dentro do `aside`.
- Combinação poderosa para layouts complexos.

 Principais Diferenças entre Flexbox e Grid

| Característica                   | Flexbox                                 | Grid + Flexbox                                           |
|----------------------------------|-----------------------------------------|----------------------------------------------------------|
| Eixo principal                   | Um eixo por vez (linha ou coluna)       | Trabalha em **duas dimensões** (linhas e colunas)        |
| Controle do layout               | Mais limitado para estruturas complexas | Mais preciso para áreas maiores e layouts responsivos    |
| Alinhamento interno              | Ótimo para componentes e conteúdo       | Flexbox é usado em conjunto para alinhar conteúdo        |
| Complexidade da estrutura        | Mais simples, mas pode virar "gambiarra"| Requer mais planejamento, mas oferece clareza            |
| Reutilização                     | Mais direto                             | Mais modular com áreas definidas                         |

Conclusão

- O **Flexbox** é ótimo para **componentes e layouts simples** em uma dimensão (horizontal OU vertical).
- O **CSS Grid**, combinado com Flexbox, é ideal para **layouts mais estruturados**, como páginas completas com áreas distintas e bem definidas.
- A escolha entre um ou outro (ou ambos) depende da complexidade e da flexibilidade necessária para o projeto.
