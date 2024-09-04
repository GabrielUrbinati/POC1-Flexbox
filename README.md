 # POC1-Flexbox
Prova de conceito sobre as propriedades Flexbox.

<a id="readme-top"></a>

<br />
<div align="center">
  <a href="https://github.com/GabrielUrbinati/POC1-Flexbox">
    <img src="POC1/README/imagensPOC1/flexbox1.jpeg" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">POC - Flexbox</h3>

  <p align="center">
  O objetivo desta prova de conceito é ajudar os usuários a entender e aplicar HTML e CSS, com foco específico em Flexbox, proporcionando uma base sólida para a criação de layouts responsivos e flexíveis.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <ul>
        <li><a href="#prerequisites">Prerequisitos</a></li>
      </ul>
    </li>
    <li><a href="#usage">Uso</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contatot</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Este projeto é parte do segundo semestre do curso de Sistemas de Informação do Mackenzie, na disciplina de Web Mobile. Trata-se da primeira prova de conceito, com uma abordagem extensiva que visa ampliar o conhecimento na área e promover um impacto positivo na comunidade. O objetivo é ajudar os usuários a entender e aplicar HTML e CSS, com foco específico em Flexbox, proporcionando uma base sólida para a criação de layouts responsivos e flexíveis.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Construído com

* HTML5
* CSS

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Prerequisitos para começar a usar flexbox


1. Conhecimento Basico de HTML e CSS
HTML: Entendimento de como estruturar documentos HTML com elementos e atributos.
CSS: Compreensao de como aplicar estilos aos elementos HTML, incluindo seletores, propriedades e valores.

2. Conceitos Fundamentais de Layout
Modelo de Caixa (Box Model): Saber como as propriedades width, height, padding, border e margin afetam o layout dos elementos.
Posicionamento: Entender as propriedades de posicionamento como static, relative, absolute e fixed.

3. Propriedades CSS Basicas
Display: Conhecimento das propriedades display, como block, inline, inline-block, e none.
Margin e Padding: Compreensao de como as margens e o preenchimento afetam o espaco ao redor e dentro dos elementos.

4. Conhecimento de Layouts Basicos
Layouts de Bloco e Inline: Saber como os elementos de bloco e inline se comportam e como eles sao exibidos em relacao ao fluxo do documento.

5. Navegadores e Ferramentas de Desenvolvimento
Compatibilidade de Navegadores: Saber que Flexbox e amplamente suportado pelos navegadores modernos, mas pode ter algumas diferencas de implementacao.
Ferramentas de Desenvolvimento: Usar ferramentas de desenvolvimento do navegador para inspecionar e depurar layouts flexiveis.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Uso


 Flexbox pode ser usado para criar um layout basico onde os itens sao distribuídos uniformemente ao longo do contêiner.

1. Alinhamento Horizontal

  Alinhe itens horizontalmente ao longo do eixo principal com diferentes opcoes de alinhamento, como centralizado, ao inicio ou ao final.

2. Alinhamento Vertical

Alinhe itens verticalmente ao longo do eixo transversal, ajustando a posicao dos itens em relacao ao contêiner.
Layout em Colunas e Linhas

3. Use a propriedade flex-direction para alternar entre layouts em coluna e linha, permitindo organizar os itens    verticalmente ou horizontalmente.

4. Embutir Layouts Flexiveis

  Utilize Flexbox dentro de outros contêineres flexiveis para criar layouts mais complexos e responsivos.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] **Crie um layout basico onde os itens sao distribuídos uniformemente ao longo do contêiner.**  
  *Veja: `display: flex;`*
   ![Exemplo de Layout Basico](POC1/README/imagensPOC1/flex.jpeg)

- [ ] **Alinhe itens horizontalmente ao longo do eixo principal com diferentes opcoes de alinhamento, como centralizado(center), ao inicio (start) ou ao final (end).**  
  *Veja: `justify-content: center;`, `justify-content: start;`, `justify-content: end;`*
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/JC-center.jpeg)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/JC-start.jpeg)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/JC-end.jpeg)

- [ ] **Alinhe itens verticalmente ao longo do eixo transversal, ajustando a posicao dos itens em relacao ao contêiner no centro (center), ao inicio (start) ou ao final (end)**  
  *Veja: `align-items: center;`, `align-items: start;`, `align-items: end;`*
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/align-items-center.jpeg)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/align-items-start.jpeg)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/align-items-end.jpeg)

- [ ] **Use a propriedade `flex-direction` para alternar entre layouts em coluna e linha, permitindo organizar os itens verticalmente ou horizontalmente e de forma inversa.**  
  *Veja: `flex-direction: row;`, `flex-direction: row-reverse;`, `flex-direction: column;`, `flex-direction: column-reverse;`*
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/direc-row.jpeg)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/row-reverse)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/direc-column.jpeg)
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/column-reverse.jpeg)

- [ ] **Utilize Flexbox dentro de outros contêineres flexiveis para criar layouts mais complexos e responsivos.**  
  *Veja: `flex-wrap: nowrap;`, `flex-wrap: wrap;`, `flex-wrap: wrap-reverse;`*
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/nowrap.jpeg) - Os itens flexíveis permanecem em uma única linha, sem quebra. Isso pode resultar em overflow se o conteúdo exceder o espaço disponível. 
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/wrap.jpeg) - Os itens flexíveis quebram em várias linhas, se necessário, para se ajustarem ao contêiner. As linhas adicionais são dispostas abaixo da linha anterior.
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/wrap reverse.jpeg) - Os itens flexíveis também quebram em várias linhas, mas as linhas adicionais são dispostas acima da linha anterior, invertendo a ordem padrão de empilhamento.

- [ ] **Crie layouts flexiveis com diferentes opcoes de justificacao e alinhamento.**  
  *Veja: `justify-content: space-around;`, `justify-content: space-between;`*
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/JC-space-around.jpeg)- Distribui os itens de forma que o espaço restante é dividido igualmente entre eles, colocando o primeiro item no início e o último no final da linha.
  ![Exemplo de Layout Basico](POC1/README/imagensPOC1/JC-space-between.jpeg) - Distribui os itens de forma que o espaço restante é dividido igualmente entre eles, colocando o primeiro item no início e o último no final da linha.

<p align="right">(<a href="#readme-top">back to top</a>)</p>







