# Fibra Bruta

Plataforma demonstrativa de gestão para provedores de internet. A primeira versão inclui landing page, painel de operação responsivo, dados sintéticos e estrutura inicial Cloudflare D1.

## Rodar localmente

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Conteúdo da demonstração

- Landing page da marca Fibra Bruta e painel com navegação por 26 áreas.
- Indicadores, listas, busca, filtros, formulários, detalhes, exportação CSV e persistência local no navegador.
- Dados exclusivamente fictícios. Não inserir informações reais de assinantes nesta versão.
- Integrações externas aparecem em modo de demonstração, sem conexão com gateways, RADIUS, OLT, WhatsApp, NFCom ou assinatura eletrônica.
- O painel da primeira versão é um protótipo público e não implementa autenticação de produção. O banco D1 contém dados sintéticos e uma estrutura inicial multi-tenant; antes de receber dados reais, devem ser concluídos API autenticada, gestão de sessões, autorização por tenant e trilha de auditoria no servidor.

## Estrutura

- `src/main.js` e `styles.css`: aplicação visual e interações demonstrativas.
- `public/assets/fibra-bruta-logo.png`: logo aprovada em PNG com fundo transparente.
- `cloudflare/migrations/0001_initial.sql`: schema e registros sintéticos iniciais do D1.
- `docs/modulos-planejados.md`: mapa funcional de referência.
- `netlify.toml`: build estático e cabeçalhos básicos de segurança.

Todos os números de operação, nomes, contatos, valores e eventos da interface são dados fictícios.
