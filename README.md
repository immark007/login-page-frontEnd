# 🚀 Login e Cadastro - Angular

Este é um projeto Angular que implementa uma página de login e cadastro com estrutura modularizada. Ele está preparado para consumir um back-end futuramente.  

## 📌 Tecnologias Utilizadas

- Angular
- TypeScript
- SCSS para estilização
- Angular Services para integração com APIs futuras

## 📂 Estrutura do Projeto

```
src/
│── app/
│   ├── components/                # Componentes reutilizáveis
│   │   ├── default-login-layout/  # Layout padrão para login
│   │   ├── primary-input/         # Componente de input reutilizável
│   ├── pages/
│   │   ├── login/
│   │   │   ├── login.component.html   # Template HTML
│   │   │   ├── login.component.scss   # Estilos da página de login
│   │   │   ├── login.component.ts     # Lógica do componente
│   │   │   ├── login.component.spec.ts # Testes do componente
│   │   │   ├── services/
│   │   │   │   ├── login.service.ts   # Service para requisições HTTP
│   │   │   │   ├── login.service.spec.ts # Testes do service
│   │   │   ├── types/
│   │   │   │   ├── login-response.type.ts # Interface para tipagem de resposta da API
│   ├── app.component.html          # Template principal
│   ├── app.component.scss          # Estilos globais
│   ├── app.component.ts            # Componente raiz
│   ├── app.config.ts               # Configuração global
│   ├── app.routes.ts               # Rotas da aplicação
```

## 📦 Instalação e Execução

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/immark007/login-page-frontEnd.git
```

### 2️⃣ Instalar as dependências
```bash
cd login-page-FrontEnd
npm install
```

### 3️⃣ Rodar o servidor de desenvolvimento
```bash
ng serve
```

A aplicação estará disponível em: [http://localhost:4200](http://localhost:4200)

## 🛠 Funcionalidades

✅ **Login:** Formulário de login com campos de e-mail e senha.  
✅ **Cadastro:** Interface planejada para permitir o registro de novos usuários.  
✅ **Serviço de Autenticação:** Um `login.service.ts` para futura comunicação com o back-end.  
✅ **Tipagem forte com TypeScript:** Interfaces e types definidos no diretório `types/`.  
✅ **Componentização:** Elementos reutilizáveis em `components/` para facilitar a manutenção.  
✅ **Estilização modularizada:** Uso de SCSS para estilos específicos de cada página.  

## 🚀 Próximos Passos

🔹 Integrar com um back-end para autenticação real.  
🔹 Implementar proteção de rotas com Guards do Angular.  
🔹 Criar uma página de dashboard após o login.  

---
