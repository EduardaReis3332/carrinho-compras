## GitHub Pages

A aplicação está hospedada no GitHub Pages. Você pode acessá-la [aqui](https://eduardareis3332.github.io/carrinho-compras/index.html).

# Carrinho de Compras com Vue.js e Supabase

## Descrição do Projeto

Este projeto implementa um carrinho de compras simples usando Vue.js para o frontend e Supabase como backend para armazenar os dados do carrinho. A aplicação permite aos usuários adicionar itens ao carrinho, remover itens e finalizar a compra, salvando os dados no banco de dados do Supabase.

## Instruções de Instalação e Execução

### Requisitos

- Navegador da web
- Node.js (para desenvolvimento)

### 1. Clonar o Repositório

```bash
git clone https://github.com/EduardaReis3332/carrinho-compras.git
cd carrinho-compras
```

### 2. Configurar as Credenciais do Supabase

1. Crie uma conta no Supabase (https://supabase.io/).
2. Crie um projeto no Supabase e obtenha as credenciais (URL do banco de dados e chave de API).

### 3. Configurar o Projeto

Abra o arquivo no editor de código e substitua as seguintes linhas com suas credenciais do Supabase:

```bash
const supabaseUrl = 'URL_DO_SEU_PROJETO_SUPABASE';
const supabaseKey = 'CHAVE_DA_SUA_API_SUPABASE';
```

### 4. Executar a Aplicação

Existem várias maneiras de executar a aplicação. Você pode simplesmente abrir o arquivo `index.html` no seu navegador ou usar um servidor web local. Se você tiver o Node.js instalado, pode usar o `serve` para iniciar um servidor local:

```bash
npx serve
```

Abra o navegador e acesse `http://localhost:5000` (ou outra porta fornecida pelo servidor local).

## Estrutura do Código (Padrão MVC com Vue.js)

O código segue a estrutura do padrão Model-View-Controller (MVC) com Vue.js. Aqui está uma visão geral da estrutura:

- `index.html`: O arquivo principal que inclui o Vue.js, o Bootstrap e o script principal;O script Vue.js que define a lógica da aplicação; Estilos adicionais usando Bootstrap.
- `README.md`: Este arquivo, documentando o projeto.

## Funcionalidades Implementadas

- Adicionar itens ao carrinho.
- Remover itens do carrinho.
- Finalizar a compra e salvar os dados no Supabase.