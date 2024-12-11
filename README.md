# Portif-lio-
# README - Site Portfólio com Menu Hambúrguer

Este documento descreve os detalhes do projeto de um site portfólio pessoal que inclui um menu hambúrguer responsivo. O objetivo é exibir informações sobre experiências, projetos e habilidades de maneira atrativa e acessível em diferentes dispositivos.

## Sobre o Projeto

- **Nome do Projeto:** Site Portfólio  
- **Descrição:** Este projeto é um site responsivo desenvolvido para apresentar portfólio pessoal. Ele inclui um menu hambúrguer intuitivo para facilitar a navegação em dispositivos móveis.  
- **Funcionalidades Principais:**
  - Apresentação de informações pessoais e profissionais.
  - Exibição de projetos com descrições e links.
  - Menu hambúrguer responsivo para navegação simplificada.

## Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript  
- **Design:** Google Fonts para estilização de texto.

## Requisitos

- Navegador atualizado (Google Chrome, Mozilla Firefox, etc.).
- Conexão com a internet para recursos externos (Google Fonts).

## Instalação

1. Clone o repositório:
   ```bash
   git clone [URL do repositório]
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd portfolio-site
   ```
3. Abra o arquivo `index.html` no navegador ou inicie um servidor local (opcional):
   ```bash
   [Comando para iniciar servidor local, ex.: npx live-server]
   ```

## Estrutura do Projeto

- **index.html:** Estrutura principal do site.
- **css/style.css:** Estilo para a página principal.
- **css/menu.css:** Estilo específico para o menu hambúrguer.

## Funcionalidades do Menu Hambúrguer

- O menu hambúrguer é exibido automaticamente em dispositivos com telas menores.
- Ao clicar no ícone do menu, uma animação responsiva abre o menu com links de navegação.
- Links:
  - Início
  - Projetos
  - Sobre mim
  - Contato

## Personalização

- **Cores e estilos:** As cores e as animações podem ser personalizadas nos arquivos `menu.css` e `style.css`.
- **Conteúdo:** Atualize o arquivo `index.html` para incluir suas próprias informações, como nome, descrição e links para projetos.

## Exemplo de Códigos

### HTML (index.html)

```html
<!DOCTYPE html>
<html>
<head>
	<title>Apresentação</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="stylesheet" type="text/css" href="css/menu.css">
	<link href="https://fonts.googleapis.com/css?family=Dancing+Script:700|Roboto&display=swap" rel="stylesheet">
</head>
<body>
	<div class="menu-wrap">
		<input type="checkbox" class="toggler">
		<div class="hamburger">
			<div></div>
		</div>
		<div class="menu">
			<div>
				<div>
					<ul>
						<li><a href="#">Início</a></li>
						<li><a href="#">Projetos</a></li>
						<li><a href="#">Sobre mim</a></li>
						<li><a href="#">Contato</a></li>
					</ul>
				</div>
			</div>
		</div>
	</div>
    <div class="container">
    	<div class="content">
    		<h2>Rômulo Richard</h2>
    		<p>Desenvolvedor Full Stack</p>
    		<a href="#" class="btn">Saiba mais</a>
    	</div>


![image](https://github.com/user-attachments/assets/d36d9fa7-0762-4185-8c9a-2ffdaa45590a)
![image](https://github.com/user-attachments/assets/6a1caf2d-7785-4729-9ded-e8e7215006fa)
