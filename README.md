# Upload de Vídeos com IA

Esta é a interface da aplicação desenvolvida durante a Next Level Week (NLW) da Rocketset, na trilha Mastery. Ela permite que você faça upload de seus vídeos e, com a ajuda da inteligência artificial, cria automaticamente títulos chamativos e descrições otimizadas para uma melhor indexação nos mecanismos de busca. O front-end é construído em React com as bibliotecas Tailwind CSS, Shadcn/UI e Radix UI, enquanto o back-end utiliza Node.js com Fastify, o banco de dados é gerenciado com Prisma, e a IA é alimentada pela API da OpenAI.

![image](https://github.com/karGuimaraes/nlw-upload-ai/assets/39937365/9e839fe3-fe7a-47c7-bfae-96933511a93c)


## Tecnologias Utilizadas

### Front-end

- **React**: Utilizado para construir a interface do usuário da aplicação, proporcionando uma experiência de usuário dinâmica e responsiva.

- **Tailwind CSS**: Utilizado para estilizar a aplicação de forma rápida e consistente.

- **Shadcn/UI**: Componentes elegantes utilizados para aprimorar a experiência do usuário.

- **Radix UI**: Componentes de alta qualidade para melhorar a usabilidade da aplicação.

### Back-end

- **Node.js**: Utilizado para criar o servidor e lidar com a lógica do lado do servidor.

- **Fastify**: Framework web utilizado para criar uma API REST rápida e eficiente.
## Como Usar

1. Clone este repositório:

```bash
git clone https://github.com/karGuimaraes/nlw-upload-ai.git
```

2. Acesse o diretório do front-end:

```bash
cd nlw-upload-ai/upload-ai-web
```

3. Instale as dependências do front-end:

```bash
npm install
```

4. Acesse o diretório do back-end:

```bash
cd ..
cd upload-ai-api
```

5. Instale as dependências do back-end:

```bash
npm install
```

6. Configure o banco de dados no arquivo `.env` no diretório `upload-ai-api` e execute as migrações do Prisma:

```bash
npx prisma migrate dev
```

7. Inicie o servidor do front-end:

```bash
cd ..
cd upload-ai-web
npm start
```

8. Inicie o servidor do back-end:

```bash
cd ..
cd upload-ai-api
npm start
```
