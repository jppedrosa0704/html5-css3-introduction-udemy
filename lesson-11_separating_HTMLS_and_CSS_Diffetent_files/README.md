📘 Projeto de Estudo – HTML & CSS (Especificidade, Herança e Seletores)
Este repositório contém um projeto simples desenvolvido para praticar conceitos fundamentais de HTML e CSS, com foco em:

Estrutura semântica do HTML

Seletores CSS (simples, compostos e combinadores)

Especificidade e hierarquia

Herança de propriedades

Comportamento de classes e seletores descendentes

O código demonstra como diferentes seletores podem afetar elementos semelhantes dependendo da sua posição no DOM e da força de cada regra CSS.

📂 Estrutura do Projeto
Código
/
├── index.html
└── assets/
    └── css/
        └── styles.css
🎯 Objetivo do Exercício
O projeto foi criado para treinar:

✔ Seletores CSS
element element

div p

.classe

.classe1.classe2

.pai > .filha

div.main-content2 h2.title

✔ Especificidade
Demonstra como regras mais específicas substituem regras genéricas, mesmo que apareçam antes no arquivo.

✔ Herança
Mostra como propriedades como color podem ser herdadas ou sobrescritas dependendo do seletor aplicado.

🧩 Destaques do Código
🔹 Reset básico
css
* {
  margin: 0;
  padding: 0;
}
🔹 Seletores encadeados
css
body div section p {
  color: brown;
}
🔹 Classes reutilizáveis
css
.color-blue {
  color: blue;
}
🔹 Especificidade maior com classes + elementos
css
div.main-content2 h2.title {
  color: red;
}
🔹 Combinador de filho direto
css
.pai > .filha {
  color: red;
}
🖥 Demonstração do HTML
O arquivo HTML contém:

Títulos e parágrafos estilizados por diferentes seletores

Divs com classes específicas para testar herança

Estrutura de “pai e filha” para demonstrar o combinador >

Conteúdo simples para visualizar claramente o efeito de cada regra CSS

🚀 Como visualizar
Basta abrir o arquivo:

Código
index.html
em qualquer navegador.

📌 Tecnologias Utilizadas
HTML5

CSS3

📄 Licença
Este projeto é apenas para fins educacionais.
Sinta-se à vontade para usar, modificar e estudar o código.
