# Arquivos detalhados
Este documento contém as respectivas informações em relação aos arquivos designados ao projeto do web catálogo para a empresa Iguassu Master Clean

---

## Estrutura do projeto

```shell
IMC website/
│
├── index.html
├── produtos.html
│
└── resources/
    ├── css/
    │   └── style.css
    │
    ├── fonts/
    │   ├── orkney-bold.otf
    │   ├── orkney-light.otf
    │   ├── orkney-medium.otf
    │   ├── orkney-regular.otf
    │   └── SIL Open Font License.txt
    │
    ├── img/
    │   ├── Captura_de_tela_2025-10-27_095257-removebg-preview.svg
    │   └── Iguaçu logo.png
    │
    └── js/
        └── script.js
```

---

## Arquivos HTML

### index.html
Arquivo que contém a estrutura base do sistema, sendo a página inicial do projeto. É responsável pela primeira apresentação da empresa ao usuário, reunindo informações breves e elementos visuais que destacam sua identidade e seus principais conteúdos.

A página é dividida em **header**, **main** e **footer**, cada um com uma função específica:

- ***Header***: Apresenta a logo, os elementos de navegação entre as páginas e recursos como contato e pesquisa.

- ***Main***: Contém o conteúdo principal da página, utilizando elementos visuais e textuais para apresentar a empresa e direcionar o usuário às principais áreas do catálogo.

- ***Footer***: Reúne informações complementares, como localização, horários, contato e outras informações úteis ao usuário.

### produtos.html
Arquivo responsável pela apresentação dos produtos em formato de catálogo. Possui, além do header padrão, um sistema próprio de navegação e filtragem por categorias e marcas parceiras.

Os produtos são apresentados em *cards*, permitindo ao usuário realizar buscas, ordenar os resultados em A-Z ou Z-A e escolher a quantidade de produtos exibidos na página.

---

## Arquivos CSS

### style.css
Arquivo responsável por toda a estilização visual do projeto. Contém as definições de cores, fontes, tamanhos, espaçamentos, posicionamento e efeitos dos elementos presentes nas páginas.

Também reúne as regras de responsividade, utilizando recursos como *Flexbox*, *Grid* e *Media Queries* para adaptar a interface a diferentes tamanhos de tela.

---

## Arquivos JavaScript

### script.js
Arquivo responsável pelas funcionalidades e interações do sistema. É utilizado principalmente para controlar os recursos dinâmicos do catálogo, como filtros, busca, ordenação e quantidade de produtos exibidos.

Também contém funções responsáveis por outras interações da interface, fazendo com que os elementos respondam às ações realizadas pelo usuário.

---

## Recursos visuais

### fonts/
Pasta responsável por armazenar as fontes utilizadas no projeto. Contém diferentes variações da fonte **Orkney**, utilizadas para manter uma identidade visual consistente entre os diferentes elementos da página.

Também possui o arquivo SIL Open Font License.txt, referente à licença da fonte utilizada.

### img/
Pasta destinada às imagens utilizadas no projeto, principalmente elementos relacionados à identidade visual da empresa, como a logo da Iguassu Master Clean e outros recursos gráficos utilizados na interface.

---

Voltar para a [Página Inicial](../README.md)
