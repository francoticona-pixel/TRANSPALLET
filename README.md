# TRANSPALLET — Monitoramento industrial

Dashboard web educacional para simular e acompanhar um processo de paletização.

## Tecnologias
- HTML5, CSS3 e JavaScript (ES Modules)
- Vite
- Chart.js
- Lucide

## Executar localmente
Requer Node.js 20+.

```bash
npm install
npm run dev
```

## Build de produção
```bash
npm run build
```
A saída é gerada em `dist/`.

## Funcionalidades
- Indicadores de produção atualizados automaticamente.
- Meta configurável por lote.
- Palete visual com 24 posições.
- Simulação de operação, parada e falha.
- Sensores e comunicação CLP simulados.
- Histórico de atividades e gráfico de produção.

**Aviso:** dados e comandos são simulados. O sistema não se conecta nem comanda máquinas reais.