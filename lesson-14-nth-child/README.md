📄 Lista Estilizada com Seletores nth-child
Este projeto demonstra o uso de seletores estruturais do CSS para aplicar estilos condicionais a elementos de lista. A página HTML contém uma lista <ul> com múltiplos itens, cada um recebendo estilos diferentes conforme sua posição.

📁 Estrutura do Projeto
Código
📦 projeto-nth-child
│
├── index.html
└── assets/
    └── css/
        └── styles.css
🧩 Descrição
O objetivo deste projeto é apresentar, de forma prática, como o CSS pode manipular padrões visuais utilizando seletores matemáticos como nth-child(even), nth-child(odd), nth-child(3n) e nth-child(3n + 2).

Esses seletores permitem criar estilos alternados, destacar itens específicos e aplicar regras visuais com base na posição do elemento dentro da lista.

🎨 Estilos Aplicados
🔹 Itens pares
css
ul li:nth-child(even) {
  background-color: darkorchid;
}
🔹 Itens ímpares
css
ul li:nth-child(odd) {
  background-color: rgb(196, 242, 255);
}
🔹 Múltiplos de 3
css
ul li:nth-child(3n) {
  background-color: darkgoldenrod;
  font-size: large;
}
🔹 Padrão 3n + 2
css
ul li:nth-child(3n + 2) {
  background-color: rgb(11, 184, 40);
  font-size: large;
}
🚀 Tecnologias Utilizadas
HTML5

CSS3

Seletores estruturais (nth-child)

🎯 Objetivo Educacional
Este projeto é ideal para quem está aprendendo CSS e deseja:

Entender seletores estruturais

Criar padrões visuais dinâmicos

Manipular listas com lógica matemática

Explorar comportamento de pseudo-classes
