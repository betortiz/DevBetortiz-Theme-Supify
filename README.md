# :wave: Say hi to Elizabeth :wave:

[![Generic badge](https://img.shields.io/badge/course%20available%3F-yes-green.svg)](https://shields.io/)

This project is created and intended to be used for the [Shopify Theme Development – Online Store 2.0 + TailwindCSS course](https://weeklyhow.com/courses/)


[Get the course!](https://weeklyhow.com/) | [Lessons covered](#lessons-covered) |
[How to use](#how-to-use) | [Not a student?](#not-a-student)

## Lessons covered

Status | Lectures
------------ | -------------
:heavy_check_mark: | Installing Development Tools
:heavy_check_mark: | Navigational Bar
:heavy_check_mark: | 404 Page
:heavy_check_mark: | Article Page
:heavy_check_mark: | Blog Page
:heavy_check_mark: | Cart Page
:heavy_check_mark: | Product Collection Page
:heavy_check_mark: | Collections Page
:heavy_check_mark: | Homepage (Index)
:heavy_check_mark: | Pages (About & Contact)
:heavy_check_mark: | Advanced Product Page
:heavy_check_mark: | Search Page
:hourglass: | More lessons coming

## How to use

To use this repository for making Shopify themes, use the following command of Shopify CLI.
```sh
shopify theme init [ NAME OF YOUR THEME ] --clone-url https://github.com/polidario/Elizabeth_Clean
```

If you don't have Shopify CLI installed to your computer, navigate to the [installation page of Shopify CLI](https://shopify.dev/themes/tools/cli/installation).

## Not a student

If you're not a student, you can still use this repository to start a new Shopify theme project. However, any issues that you will encounter throughout your development will not be supported as the instructor will only answer questions through the course's QnA page.


### Install Ruby
[link instalação do Ruby](https://rubyinstaller.org/downloads/)

version  Ruby+Devkit 3.2.4-1 (x64)


### Install Shopify CLI
```bash
npm install -g @shopify/cli@latest
```

## Instalar o Tailwind
[Pagina de instalação Tailwind](https://tailwindcss.com/docs/installation)
# Arquivo tailwind.config.js
```bash
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    './layout/*.liquid',
    './sections/*.liquid',
    './snippets/*.liquid',
    './templates/*.liquid',
    './templates/customers/*.liquid'
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

```
# Comando para criar a saida do tailwind
```bash
npx tailwindcss -1 ./src/tailwind.css -o ./assets/application.css
```


# Git project clean
[link do projeto clean no github](https://github.com/polidario/Elizabeth_Clean)
# Comando para clonar o repositorio para o shopify
```bash
shopify theme init --clone--url=https://github.com/polidario/Elizabeth_Clean.git
```

# Executar o comando abaixo:
```bash
shopify theme init
```

## Comando para conectar o projeto do vs-code na plataforma shopify
```bash
shopify theme dev --store devbetortiz.myshopify.com
```

# Comando para execução do tailwind
```bash
npx tailwindcss -i ./src/tailwind.css -o ./assets/application.css --watch
```