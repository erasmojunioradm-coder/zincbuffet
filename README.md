# ZINC V5.1 — painel profissional

Esta versão substitui o protótipo baseado em armazenamento local do navegador por uma aplicação Node/Express com arquivos persistidos no servidor.

## Instalação
1. Instale Node.js 18+
2. Abra esta pasta no terminal
3. Execute `npm install`
4. Execute `npm start`
5. Site: http://localhost:3000
6. Administração: http://localhost:3000/admin

## Acesso inicial
Usuário: `maitane`
Senha: `maitane456`

## Novidades
- Capa do site editável com upload persistente.
- Cores do site editáveis com pré-visualização.
- Temas prontos: ZINC Original, Luxo e Moderno.
- Tipografia editável.
- Salvar alterações separado de Publicar.
- Eventos e álbuns organizados.
- Upload múltiplo de fotos e vídeos.
- Publicação individual ou em lote.
- Selecionar todas / remover selecionados.
- Ordenação por arrastar e soltar.
- Ver como cliente.
- Saúde do site.
- Feedback visual de sucesso/erro.

## Produção
Para internet pública, coloque atrás de HTTPS e use um storage/backup adequado para uploads. O arquivo `data/content.json` é uma solução simples para esta etapa; para crescimento, migre para banco de dados e object storage/CDN.
