# pwiii-cristian-harold

entra na pasta e já digite composer install 


.env

.env example




npm install; npm run build 

php artisan key:generate 

php artisan migrate

composer run dev 



comandos 
php
Aula de Programação Web III com o Professor João Siles

# 🚀 Projeto Laravel - Guia Completo (Didático)

Aplicação desenvolvida com o framework Laravel para a disciplina de **Programação Web III**.

---

# 📋 Pré-requisitos

Antes de começar, você precisa ter instalado no seu computador:

* PHP (versão 8 ou superior)
* Composer
* Node.js e NPM

---

# ⚙️ Instalando o Laravel

Se você **já tem PHP e Composer instalados**, execute no terminal:

```
composer global require laravel/installer
```

Depois disso, **reinicie o terminal**.

---

## ❗ Caso NÃO tenha PHP e Composer

Abra o PowerShell como administrador e execute:

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows/8.4'))
```

Depois, feche e abra o terminal novamente.

---

# 🆕 Criando um novo projeto

No terminal (dentro da pasta onde deseja criar o projeto):

```
laravel new nome-do-projeto
```

Durante a instalação, escolha:

* React (frontend)
* Laravel (autenticação padrão)
* PHPUnit (testes)
* Laravel Boost → Enter (padrão)
* NPM build → Enter (padrão)

Depois:

```
cd nome-do-projeto
```

---

# 🔑 Configuração inicial

## 1. Arquivo .env

Copie o arquivo de exemplo:

```
cp .env.example .env
```

## 2. Gerar chave da aplicação

```
php artisan key:generate
```

---

# 🗄️ Banco de dados

O Laravel usa **migrations**, que são arquivos para criar tabelas no banco.

Antes de rodar, configure o banco no arquivo `.env`.

Depois execute:

```
php artisan migrate
```

---

# 🎨 Front-end

Instale as dependências:

```
npm install
```

Compile o projeto:

```
npm run build
```

Durante o desenvolvimento:

```
npm run dev
```

---

# ▶️ Rodando o projeto

Para iniciar o servidor:

```
php artisan serve
```

Acesse no navegador:

```
http://localhost:8000
```

---

# 🔄 Clonar projeto existente (GitHub)

Se você baixou o projeto, execute:

```
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install
npm run build
```

---

# 🧰 Comandos úteis

Criar uma nova view:

```
php artisan make:view nome
```

Criar uma migration:

```
php artisan make:migration nome_da_tabela
```

---

# 📚 Dicas importantes

* Sempre que alterar o front-end → rode `npm run build`
* Nunca apague o arquivo `.env.example`
* Se algo não funcionar, tente:

  * reiniciar o terminal
  * rodar `composer install` novamente

---

# 📖 Documentação oficial

https://laravel.com/docs

---

# ✅ Resumo rápido

1. Instalar dependências
2. Criar projeto (`laravel new`)
3. Configurar `.env`
4. Rodar migrations
5. Rodar `npm install`
6. Rodar `php artisan serve`

---

💡 Pronto! Seu projeto Laravel já estará funcionando 🚀

