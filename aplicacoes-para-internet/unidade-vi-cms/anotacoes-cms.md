<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href='https://fonts.googleapis.com/css?family=Fira Code' rel='stylesheet'>
    <style>
        * {
            font-family: 'Fira Code';
            font-size: 18px;
        }
    </style>
</head>
<body>
</body>
</html>

# CMS

## Conceito

CMS (**_Content Management System_**) é um Gerenciador de Conteúdo de Sistema, onde realiza a organização de acesso aos conteúdos de cada usuário além de permitir que tal usuário com o devido acesso, posso editar o conteúdo exibido nas páginas, sem precisar ter conceito de HTML.

WCMS (**_Web Content Management System_** ou **_Sistema Gerenciador de Conteúdo_**). É uma aplicação web que fornece recursos para vários usuários com diferentes níveis de permissão para gerenciar a página web (conteúdo), sem a necessidade de ter conhecimento de HTML, fornecendo recursos para vários níveis de usuários com diferentes permissões de gerenciamento.

**Obs:** Gerenciamento de conteúdo refere-se à criação, edição, arquivamento, publicação, colaboração, dados e informações de um site.

## Algumas opções do mercado

O **Drupal** é comumente descrito como um Framework de Gerenciamento de Conteúdo, pois além de oferecer as funcionalidades básicas de um CMS ele também implementa uma série de APIs robustas e apresenta uma estrutura modular que facilita o Fdesenvolvimento de módulos extensivos.

**Redaxscript** é um Gerenciador de Conteúdo de Código Aberto muito poderoso, cheio de recursos para ajudar a desenvolver todos portes de sites, desdo do pequeno até mais grandes. Compatível também com dispositivos mobiles e SEO (**_Search Engine Optimization_**). Desenvolvido em PHP e utilizando o MySQL como SGBD, trabalhando também com HTML5 e CSS3.

O **Joomla** também outro Gerenciador de Conteúdo que permite a criação e gestão de sites web dinamicos. Criado em 2006, o Joomla! tornou-se o CMS em maior expansão sendo provavelmente o CMS mais procurado, com a maior comunidade e mais recursos disponíveis.

O **Pimcore** é uma plataforma de gerenciamento de experiência digital (DXP) de código aberto que oferece uma variedade de recursos para criar, gerenciar e distribuir conteúdo digital de forma eficiente. Ele combina gerenciamento de conteúdo (CMS), gerenciamento de informações de produtos (PIM), gerenciamento de ativos digitais (DAM) e comércio eletrônico em uma única solução integrada.

Sendo uma solução altamente flexível e personalizável, adequada para uma ampla gama de casos de uso, desde pequenas empresas até grandes empresas que buscam uma plataforma unificada para gerenciar sua presença digital de forma eficiente. Sua natureza de código aberto também significa que é suportado por uma comunidade ativa de desenvolvedores e possui uma ampla gama de plugins e extensões disponíveis.

**Mambo** é um CMS Open Source, voltado também para aplicações comerciais/proprietárias. Com um corpo técnico para o desenvolvimento de
aplicações baseadas no conjunto AMP (Apache, MySQL e PHP).

O famoso **WordPress** é WCMS escrito em PHP com banco de Dados MySQL, voltado principalmente para a criação de sistes e blogs via web. Que bate de frente com a ferramenta do Google chamada Blogger.

Tem também o **opencart** que é sistema de E-Commerce Open Source criado por Daniel Kerr utilizando PHP, licenciado nos termos da GNU (General Public License). É gratuito como mencionado e voltado para criação e gestão de loja virtual, focado na facilidade de instalação e utilização.

## Conceitos da arquitetura cliente/servidor

Na arquitetura cliente/servidor, o computador cliente envia uma solicitação para o servidor através da conexão de rede, que é então processada pelo servidor que retorna a resposta para o cliente. A Internet também é baseada na arquitetura cliente/servidor em que o servidor Web serve a muitos clientes em simultâneo alguns serviços como acesso a sites.

Em resumo funciona assim: (1) O cliente faz a requisição através de um URL (Uniform Resource Locator) ou Localizador-Padrão de Recursos. (2) Tal requisição passa para o Web server que busca o html retornonando a parte visual. (3) Também busca pelo arquivo PHP que comunica com a base de dados MySQL, que tal base de dados retorna tal informação onde o arquivo php processa de acordo com o que foi pedido. (4) Retona essa informação para o php do web server onde o web server retonar a resposta para a internet, onde por fim chega ao lado do cliente.

## O que é PHP?

O PHP (um acrônimo recursivo para PHP: (Hypertext Preprocessor) é uma
linguagem de script open source de uso geral, muito utilizada, e especialmente
adequada para o desenvolvimento web e que pode ser embutida dentro do HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <?php
// Seu código PHP aqui
echo "Olá, mundo!";
?>
  </body>
</html>
```

**Explicação:**

Observe no exemplo acima que temos um mix de html com php. O código php, somente pode ser interpretado pelo servidor, que nesse caso é o nosso servidor Apache. O browser iria retornar somente o código html

### Servidor Apache

O servidor Apache (ou Servidor HTTP Apache, em inglês: Apache HTTP Server, ou simplesmente: Apache) é o servidor web livre mais utilizado do mundo.
Foi criado em 1995 por Rob McCool, então funcionário do NCSA (National Center for Supercomputing Applications). Em uma pesquisa realizada em dezembro de 2007, foi constatado que a utilização do Apache representa cerca de 47.20% dos servidores ativos no mundo. Em maio de 2010, o Apache serviu aproximadamente 54,68% de todos os sites e mais de 66% dos milhões de sites mais movimentados.

É a principal tecnologia da Apache Software Foundation, responsável por mais de uma dezena de projetos envolvendo tecnologias de transmissão via web, processamento de dados e execução de aplicativos distribuídos. O servidor é compatível com o protocolo HTTP versão 1.1. Suas funcionalidades são mantidas através de uma estrutura de módulos, permitindo inclusive que o usuário escreva seus próprios módulos — utilizando a API do software. É disponibilizado em versões para os sistemas Windows, Novell Netware, OS/2 e diversos outros do padrão POSIX (Unix, Linux, FreeBSD, etc.).

## Servidor de Banco de Dados

O MySQL é o um banco de dados de código aberto mais popular, confiavél, performático e facil de usar. Principal opção de banco de dados para apps baseados na Web, usados por Facebook, Twitter, Youtube. Além de ser uma pção extremamente popular como banco de dados integrado, distribuidos por milhares de **_ISVs e OEMs_**

**Obs:** ISVs (Independent Software Vendors) e OEMs (Original Equipment Manufacturers) são dois tipos de empresas na indústria de software, cada uma desempenhando papéis distintos no desenvolvimento, distribuição e venda de software.

Em resumo, os ISVs são empresas que criam e vendem software como produto independente, enquanto os OEMs são empresas que integram software em produtos físicos que vendem. Embora possam colaborar, eles desempenham papéis distintos no ecossistema de software e hardware.

### Ferramentas necessárias para utilizar um CMS

Iremos usar o CMS WordPress e precisaremos configurar o APACHE HTTP SERVER, PHP E MYSQL. Nesse caso podemos um dos seguintes pacotes para instalar e configurar o APACHE HTTP SERVER, PHP e MYSQL. Seria as seguintes ferramentas: **WAMP** ou **XAMP** ou **Easyphp**.
