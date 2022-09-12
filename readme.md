# DRUPAL HANDS ON TEST

## Commit 01 - Criação do primeiro commit e instalação da base drupal.
- Executado os comandos "git init" & "composer create-project drupal/recommended-project".
- Realizada inicialização do repositório.
- Disparado o comando de criação do projeto drupal.

## Commit 02 - Criação do tema do drupal/bootstrap3.
- Executado o comando composer require drupal/bootstrap3

## Commit 03 - Realizada a instalação do ambiente drupal na base de dados MySQL.
- Validado e estabilidade e o funcionamento da aplicação dentro do servidor apache.
- Realizado a criação em um ambiente MySQL para instalação da aplicação na base.
- Realizado a instalação da aplicação na base drupal_db.

### SQL para criação da base de dados.
```sql
CREATE TABLE IF NOT EXISTS `DRUPAL_DB`;
```

## Commit 04 - Configuração incial do subtheme ultilizando o drupal/bootstrap3 como base.
- Realizada a configuração para debug dos arquivos em tela no formato TWIG
```yml
  twig.config:
    debug: true
    auto_reload: true
    cache: false
```

## Commit 05 - Adicionado o dump da base de dados:
- Acesso ao sistema como admin (AMBIENTE DE DESENVOLVIMENTO) (USER: admin-dev | PASS: devDrupal@2022)
- Banco de dados MySQL versão 5.7 ou superior.
---

# Recursos desejados
- [X] Você criará um subtema e o personalizará usando CSS.
- [X] A página inicial deste site listará Filmes em destaque e o usuário deve poder clicar no 'título' do filme, 'imagem' ou 'descrição curta' para abrir a página do filme em outra guia .
- [X] A página do filme deve ter o 'título do filme', 'poster do filme', 'sinopse do filme' e a lista de atores deste filme.
- [-] A página do ator deve ter o 'nome do ator', 'foto do ator', 'biografia do ator' e a lista de filmes no site em que esse ator desempenhou um papel.
- [] Deve haver um recurso de pesquisa no cabeçalho do site. O usuário deve ser capaz de encontrar filmes e atores.
- [] Este site não aceita nenhum registro de usuário.
