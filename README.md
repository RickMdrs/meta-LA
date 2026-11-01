# Meta LA 2027

Painel para acompanhar uma meta de economia em dupla. Cada pessoa registra o que guardou ou retirou, e o painel
mostra quanto cada uma já juntou, o total, quanto falta e a contagem regressiva até a data da viagem.

**Ver no ar → [rickmdrs.github.io/meta-LA](https://rickmdrs.github.io/meta-LA/)**

## Destaques

- **Sincronização em tempo real** entre os celulares com o Firebase Realtime Database
- **Funciona sem configurar a nuvem:** sem o Firebase, os dados ficam salvos no próprio navegador
- **Histórico de movimentações** de cada pessoa
- Um único arquivo HTML, sem framework e sem etapa de build

**Stack:** HTML · CSS · JavaScript · Firebase Realtime Database · GitHub Pages

## Como rodar

Abra o `index.html` no navegador. Para sincronizar entre aparelhos, siga as instruções do bloco
`FIREBASE` no início do script e cole as chaves do seu projeto.
