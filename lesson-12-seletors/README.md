📘 HTML5 & CSS3 – Seletores Avançados
Projeto demonstrativo criado para estudo e prática de seletores CSS, combinadores, atributos e pseudo‑comportamentos.

🔗 Página publicada:  
https://jppedrosa0704.github.io/html5-css3-introduction-udemy/lesson-12-seletors/

📌 Objetivo do Projeto
Este repositório apresenta exemplos práticos de seletores CSS aplicados em estruturas HTML reais.
O foco é demonstrar como diferentes tipos de seletores influenciam o estilo dos elementos, incluindo:

Combinadores (+, ~)

Seletores de atributo

Seletores de irmãos adjacentes e gerais

Seletores condicionados por classes específicas

Estilização baseada em atributos booleanos (checked)

🧱 Estrutura do Projeto
Código
/
├── index.html
└── assets/
    └── css/
        └── style.css
🎨 Destaques do CSS Utilizado
✔️ Reset básico
css
* {
  margin: 0;
  padding: 0;
}
✔️ Combinador de irmão adjacente (+)
Aplica estilo **somente ao primeiro <p> imediatamente após um <h1> dentro de .pai:

css
.pai h1 + p {
  color: blue;
}
✔️ Combinador de irmãos gerais (~)
Aplica estilo a todos os <p> que seguem um <h1>, não apenas o primeiro:

css
.pai h1 ~ p {
  color: brown;
}
✔️ Seletores condicionados por classes
css
.mae .um ~ .dois {
  color: blueviolet;
}
✔️ Seletores de atributo
css
[meu-atributo="A"] {
  color: blue;
}

[meu-atributo="B"] {
  color: rgb(0, 255, 98);
}
✔️ Atributos booleanos (checked)
css
[checked] {
  width: 50px;
  height: 50px;
}
🧩 Conteúdo Demonstrado no HTML
O arquivo HTML contém blocos estruturados para testar diferentes seletores:

.pai → Testes com combinadores + e ~

.mae → Testes com classes e irmãos

.avo → Testes com irmãos adjacentes

Seletores de atributo aplicados em <h1>

Inputs com e sem checked para demonstrar estilização por atributo

🚀 Como visualizar
Clone o repositório:

bash
git clone https://github.com/jppedrosa0704/html5-css3-introduction-udemy.git
Acesse a pasta da lição:

bash
cd lesson-12-seletors
Abra o arquivo index.html no navegador.

Ou simplesmente acesse a versão publicada no GitHub Pages.

📚 Tecnologias Utilizadas
HTML5

CSS3

GitHub Pages para deploy

🧑‍💻 Autor
Paulo Pedrosa  
Estudante de Desenvolvimento Web e entusiasta de HTML, CSS e boas práticas de código.
