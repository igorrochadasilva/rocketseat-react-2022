# Projeto 4

## Fundamentos do Next.js

**Conceitos do Next.js**

Tradicional (SPA) -> Front-end --- (API/USERS) ---> Back-end(REST) ---(JSON)---> Front-end
Next SSR -> Front-end ---Home---> Next.JS(Servidor Node.js) ---(/users)---> Back-end(API REST) ---(JSON)---> Next.JS(Servidor Node.js) ---> Front-end
Next SSG -> Next -> Front-end ---Home---> Cache (CDN)home.html ---> Next.JS(Servidor Node.js) ---(/users)---> Back-end(API REST) ---(JSON)---> Next.JS(Servidor Node.js) ---> Front-end
Possibilitar que a página fique em cache durante um tempo, exemplo: deixar a home estática durante 10 minutos

**Criando projeto com Next.js**
- Criando projeto next com npx create-next-app@latest
- Limpando arquivos

**Figma: Ignite Shop**

**Criando rotas da aplicação**
-  Entendendo como funciona a questão das rotas no next.js

**Configurando documeto HTML**
- Criação e configuração do arquivo `_document`

**Quiz - Fundamentos do Nextj.s**

Em uma SPA, é correto afirmar que?
`A aplicação é gerada do lado do cliente, afetando o SEO`

Em qual abordagem o HTML é gerado em tempo de execução pelo lado do cliente?
`SPA`

Quando queremos criar uma rota no NextJS que receba um parâmetro slug, qual é o nome correto que deve ser dado para o arquivo?
`[slug].tsx`

## Estrutura Visual

**Configurando Stitches**

- Alternativa para o styled components
