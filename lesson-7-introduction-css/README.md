🎨 Layout com Background e Seções Estilizadas
📌 Sobre o Projeto
Este repositório apresenta uma página HTML simples criada para treinar conceitos fundamentais de CSS, incluindo:

Uso de background-image com cover

Aplicação de bordas, cores e espaçamentos

Criação de seções independentes com classes distintas

Controle de largura, altura, padding e margin

O objetivo é reforçar a estruturação de layouts e a personalização visual de elementos.

🧩 Estrutura do Código
HTML
A página contém duas seções principais:

section-one → fundo com imagem + cor + borda

section-two → fundo sólido + borda

CSS
Cada seção possui estilos próprios, incluindo:

background-color

background-image

background-size: cover

background-position: center center

border

padding

margin

width e height

🖼️ Exemplo de Estilo Aplicado
css
.section-one {
  background-color: deeppink;
  background-image: url(https://i.etsystatic.com/5147343/r/il/db73fc/299532345/il_1588xN.299532345.jpg);
  background-size: cover;
  background-position: center center;
  border: 10px solid black;
  color: aquamarine;
  width: 200px;
  padding: 15px;
  height: 150px;
  margin: 20px;
}
