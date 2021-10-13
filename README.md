# :: MARVEL ::


# Sobre o projeto:
Desenvolvimento de um site em Laravel que lista os quadrinhos da Marvel, exibe detalhes do produto e adiciona no carrinho.


# Requisitos:
Laravel versão 4.2.8
Composer versão 2.1.9


#API:
Acessar https://developer.marvel.com (faça seu cadatro para obter as chaves de consumo da API)


# Editor sugerido:
Visual Studio Code


# Clonar o repositório
git clone https://github.com/KaisaFernandaAlmeida/marvel.git


# Após clonar o repositório, entrar na pasta do projeto executando o comando
cd site_marvel


# Comando para executar o projeto
php artisan serve


# Sobre o código
No arquivo app/Http/Controllers/ConsumirApiController.php foi realizada a consumação da api
As paginas de visualização do site seguem o padrão dentro de resources/views que está separado por duas pastas: site e include,
na pasta site ficam os conteudos exclusivos de cada pagina e na pasta include, conteúdos que se repetem (header/ footer)
As rotas foram configuradas em routes/web.php


# Utilização do site:
A Home composta por um carousel e propaganda de alguns produtos, clicando no menu Produtos, 
exibe os quadrinhos disponíveis no site. Ao clicar no botão "ver mais" direciona o usuário
para a pagina detalhada do produto, e por fim clicando no botão "comprar" o usuário é direcionado 
para a pagina "carrinho" onde consegue ver detalhes da sua compra




