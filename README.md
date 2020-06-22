<h1 align="center">
  <br>
    <img src="https://i.imgur.com/d8QEHRb.png" alt="Tradução Magento 2 pt_BR" width="128" height="128" title="Tradução Magento 2 pt_BR"/> 
  <br>
  Tradução para Magento 2 em Português do Brasil (pt_BR)
  <br>
</h1>

<p align="center">  
  <a href="https://packagist.org/packages/rncosta/traducao_magento2_pt_br"><img src="https://img.shields.io/packagist/dt/rncosta/traducao_magento2_pt_br.svg" alt="Total Downloads"></a>
</p>

Esse pacote de linguagem foi gerado com base na [Tradução Oficial do Magento 2](https://crowdin.com/project/magento-2/pt-BR), transformado em repositório GIT para facilitar a intalação e atualizações.

Esse pacote possui alterações específicas para um modelo de negócios.

# Instalação

## Via Composer 

Para instalar essa tradução via [Composer](https://getcomposer.org) você precisa usar o terminal do seu servidor.

```
php bin/magento deploy:mode:set developer
composer require rncosta/traducao_magento2_pt_br:dev-master
php bin/magento setup:static-content:deploy pt_BR -f
php bin/magento c:c
```

## Manualmente

Para instalar a tradução manualmente você irá precisar acessar seu servidor.

* Crie o diretório **app/i18n/rncosta/language_pt_br**
* Efetue o [download do zip](https://github.com/rncosta/traducao_magento2_pt_br/archive/master.zip)
* Mova o conteúdo do repositório para a pasta e habilite a tradução

```
php bin/magento deploy:mode:set developer 
php bin/magento setup:static-content:deploy pt_BR -f
php bin/magento c:c
```

# Como Usar

Para começar a usar a tradução instalada vá em `Stores -> Configuration -> General -> General -> Locale options` e selecione em **Locale** a opção **Brazilian Portuguese (Brazil)**.

# Ajude

Ajude a melhorar a tradução oficial do Magento 2 para Português Brasil usando [esse link da página Crowdin](https://crowdin.com/project/magento-2/pt-BR).

# Autores
Essa tradução foi criada oficialmente para o Magento 2 usando o [Crowdin](https://crowdin.com/project/magento-2).
Esse repositório do Github foi criado por mim para facilitar e agilizar a atualização das traduções.

Essa tradução é baseada na tradução do [Rafael Corrêa Gomes](https://github.com/rafaelstz) e do [Leonardo Marquine Pereira](https://github.com/lmarquine)
