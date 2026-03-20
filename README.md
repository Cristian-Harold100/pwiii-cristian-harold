# pwiii-cristian-harold
Aula de Programação Web III com o Professor João Siles

# 🚀 Projeto Laravel

Aplicação desenvolvida com o framework Laravel.

---

## 📋 Requisitos

Antes de iniciar, instale em sua máquina:

* PHP (>= 8.x)
* Composer
* Node.js e NPM

---

## ⚙️ Instalação do Laravel (caso ainda não tenha)

Instale o instalador global do Laravel via Composer:

```bash
composer global require laravel/installer
```

Após a instalação, reinicie o terminal.

---

## 🆕 Criando um Novo Projeto

Crie um novo projeto Laravel:

```bash
laravel new nome-do-projeto
```

Durante a instalação, selecione:

* Starter kit: **React**
* Authentication: **Laravel (padrão)**
* Testing: **PHPUnit**
* Laravel Boost: **Yes (padrão)**
* NPM build: **Yes (padrão)**

Acesse a pasta do projeto:

```bash
cd nome-do-projeto
```

---

## 🔑 Configuração Inicial

Copie o arquivo de ambiente:

```bash
cp .env.example .env
```

Gere a chave da aplicação:

```bash
php artisan key:generate
```

---

## 🗄️ Banco de Dados

Configure o banco de dados no arquivo `.env` e execute:

```bash
php artisan migrate
```

---

## 🎨 Front-End

Instale as dependências:

```bash
npm install
```

Compile os arquivos:

```bash
npm run build
```

Para desenvolvimento:

```bash
npm run dev
```

---

## ▶️ Executando o Projeto

Inicie o servidor local:

```bash
php artisan serve
```

A aplicação estará disponível em:

http://localhost:8000

---

## 🔄 Instalar Projeto já existente (clonado)

Caso tenha baixado o projeto do GitHub:

```bash
composer install
```

```bash
cp .env.example .env
```

```bash
php artisan key:generate
```

```bash
php artisan migrate
```

```bash
npm install
```

```bash
npm run build
```

---

## 🧰 Comandos Úteis

Criar uma view:

```bash
php artisan make:view nome
```

Criar migration:

```bash
php artisan make:migration nome_da_tabela
```

---

## 📚 Documentação

https://laravel.com/docs

---
