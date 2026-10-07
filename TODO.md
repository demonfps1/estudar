# Entregas — Área & Perímetro: revisão interativa

## Página educacional e navegação

Criar uma página web em português do Brasil, responsiva e acessível, para um aluno do 2º ano do ensino médio aprender área e perímetro do zero. A página deve ter hero com promessa clara de estudo rápido, indicação da sequência recomendada, navegação para Comece aqui, Fórmulas, Exemplos, Erros comuns, Vídeos, Quiz, Simulado e Cola, rolagem suave, foco visível e indicador de progresso por seção.

## Fundamentos, fórmulas e exemplos visuais

Explicar área como espaço interno e perímetro como contorno usando analogias de piso, grama, tecido e cartolina versus cerca, fita, arame e rodapé. Mostrar unidades de área em m²/cm² e de perímetro em m/cm. Explicar, com desenhos acessíveis em SVG/CSS ou equivalente e descrição textual, quadrado, retângulo, triângulo e triângulo equilátero; cada fórmula deve mostrar o significado das letras e um exemplo numérico passo a passo. Destacar que a altura do triângulo é perpendicular à base. Incluir como descobrir o lado do quadrado pela área usando raiz quadrada e como descobrir um lado do retângulo a partir do perímetro.

## Situações aplicadas e conversões

Incluir figura em L resolvida tanto dividindo em retângulos quanto subtraindo um canto de um retângulo maior. Incluir voltas de arame usando perímetro multiplicado pelo número de voltas, várias peças iguais usando área de uma peça multiplicada pela quantidade, e exemplos cotidianos que primeiro identificam se a pergunta pede área ou perímetro. Explicar e exemplificar m ↔ cm, m² ↔ cm², incluindo 1 m = 100 cm e 1 m² = 10.000 cm².

## Erros comuns e vídeos

Exibir os cinco erros mais comuns: trocar área por perímetro; esquecer o /2 da área do triângulo; usar lado não perpendicular como altura; misturar unidades; converter m² como se fosse m. Cada erro deve ter alerta e correção. Criar seção de vídeos por tópico com canal, título e link, usando recomendações verificadas de Gis com Giz, Smile and Learn - Português, Dicasdemat Sandro Curió e Josias Maltez. Abrir links em nova aba com rel=noreferrer e marcar claramente sugestões cujo link ou título direto não foi confirmado, sem inventar vídeos.

## Quiz interativo de 15 questões

Implementar um quiz de exatamente 15 questões, uma por vez, sem revelar a resposta antes da tentativa, começando fácil e ficando mais difícil. Cobrir identificação de área/perímetro, fórmulas básicas, triângulo e altura, conversões, questões inversas, figura em L, arame e peças iguais. Aceitar múltipla escolha e respostas numéricas/textuais. Depois do envio, mostrar acerto/erro, explicação passo a passo e progresso; comemorar acertos. Em cada erro, registrar a habilidade/tipo e colocar automaticamente duas questões extras parecidas antes de voltar ao fluxo principal. Permitir reiniciar e manter o estado somente na sessão do navegador.

## Simulado final de 12 questões

Implementar simulado de exatamente 12 questões no estilo da prova: 4 de múltipla escolha com figura descrita/diagramada, 4 de cálculo, 2 de figura em L e 2 de voltas de arame ou peças iguais. Corrigir somente após o aluno entregar tudo, mostrar nota, percentual, respostas corrigidas e pontos fracos agrupados por habilidade, e oferecer botão para refazer.

## Cola de uma página

Criar seção final visualmente compacta e pronta para impressão com definições, fórmulas, unidades, conversões e checklist de prova. Adicionar CSS de impressão para ocultar navegação e deixar a cola legível.

## Direção visual e qualidade

Aplicar estética editorial escolar contemporânea, com fundo creme/papel, azul-petróleo de confiança, coral/amarelo para atenção, verde para acertos e vermelho suave para correções. Usar coluna editorial, linha de progresso, fita métrica como divisor, etiquetas de caderno para fórmulas e diagramas de traço grosso com áreas translúcidas. Implementar animações suaves com respeito a prefers-reduced-motion, tipografia legível, microcopy paciente e direta, sem infantilizar. Garantir acessibilidade, labels, descrições dos diagramas, contraste, teclado e ausência de overflow horizontal.

## Runtime, rotas, diagnóstico e checkpoint

A aplicação deve iniciar no runtime configurado e responder em `/`. Servir `manus-routes.json` com HTTP 200 declarando exatamente a rota `/`. Configurar diagnóstico TypeScript/JavaScript pela configuração WebDev antes da primeira leva de código. Rodar diagnóstico e build sem erros acionáveis, verificar manifesto e comportamento implementado, preservar o conteúdo em módulos legíveis e salvar um checkpoint no repositório canônico. Entregar a URL de Preview; só publicar se a publicação já estiver autorizada/configurada.
