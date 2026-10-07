# Área & Perímetro — revisão para a prova

Página educacional interativa em português do Brasil para revisar área e perímetro, com trilha visual, fórmulas, situações aplicadas, vídeos, quiz de 15 questões, simulado final de 12 questões e cola imprimível.

## Executar

```bash
npm install
npm run dev
```

A página roda na porta 3000. Para gerar a versão de produção:

```bash
npm run build
```

## Interações

- Os cards de fórmula abrem exemplos e diagramas.
- O quiz apresenta uma questão por vez; erros adicionam duas questões de reforço do mesmo tipo.
- O simulado só corrige quando todas as questões foram entregues.
- A seção final pode ser impressa com o botão “Imprimir cola”.
- O estado é local à sessão do navegador; não há login, servidor ou banco.
