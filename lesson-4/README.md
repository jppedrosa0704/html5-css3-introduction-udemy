📘 README — Cavaleiros do Zodíaco + Exemplo de Código Python
📝 Sobre o Projeto
Este repositório contém um pequeno projeto em HTML5 criado para treinar:

Estrutura básica de páginas HTML

Uso de tags de texto

Inserção de imagens

Links clicáveis

Blocos de citação (blockquote)

Exibição de código formatado (pre + code)

Escapando caracteres especiais (&lt;)

O tema escolhido foi Mú de Áries, um dos Cavaleiros de Ouro de Os Cavaleiros do Zodíaco.

🌐 Estrutura da Página HTML
A página exibe:

Um título centralizado

Uma imagem clicável

Um parágrafo com formatação variada

Um bloco de citação

Um bloco contendo código Python formatado

📄 Trecho principal do HTML
html
<h1 style="background: blueviolet; font-size: 70px; text-align: center;">
  Cavaleiros do zodíaco
</h1>

<div style="text-align: center;">
  <h2 style="color: blue;">Mú de áries</h2>

  <a href="https://ovicio.com.br/os-cavaleiros-do-zodiaco-10-fatos-sobre-mu-de-aries/" target="_blank">
    <img
      src="https://i.pinimg.com/736x/22/3c/90/223c9073d077f7fc46dc42fb10842c47.jpg"
      alt="Mú de Áries"
      width="500"
    >
  </a>
</div>
💬 Bloco de Citação
html
<blockquote cite="https://ovicio.com.br/os-cavaleiros-do-zodiaco-10-fatos-sobre-mu-de-aries/">
  <p>
    AQUI ESTOU FAZENDO UM BLOCO DE CITAÇÃO [...]
  </p>
</blockquote>
🧠 Código Python Exibido na Página
O código abaixo é mostrado dentro da página usando <pre> e <code>, com o caractere < escapado para evitar erro no HTML.

python
soma = 0
qtd = int(input("Digite o numero de perguntas: "))

i = 0
while i < qtd:
    valor = int(input("digite um número:"))
    soma += valor
    i += 1

print(soma)
🛠 Tecnologias Utilizadas
HTML5

CSS inline

Python (exemplo exibido na página)

📂 Estrutura do Repositório
Código
/
├── lesson_4_TagsForText_links_img.html
└── README.md
📌 Objetivo do Projeto
Este projeto serve como prática para:

Aprender HTML básico

Entender tags de formatação

Exibir código corretamente dentro de páginas web

Trabalhar com centralização e links

Criar conteúdo simples e organizado para GitHub
