## Dependências

- Express: rotas
- Hoppscotch: testar requisições no browser
- Typescript: Adicional ao javascript(tipagem estática)
- npm i ts-node-dev -D: restarte automático 
- Prisma

# back-end

## Entidades

### Game

- id
- title
- bannerUrl

### Ad

- id
- gameId
- name
- yearsPlaying
- discord
- weekdays
- hourStart
- hourEnd
- useVoiceChannel
- createdAt

## Casos de uso

- Listagem de games com contagem de anúncio
- Criação de novo anúncio
- Listagem de anúncio por game
- Buscar discord pelo ID do anúncio
