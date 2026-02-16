# run.commerce Dashboard — Empório do Piercing

Dashboard semanal de performance de e-commerce, desenvolvida por **run.commerce by Scheffer Consult**.

## Stack

- **React 18** + TypeScript
- **Vite** (build tool)
- **Tailwind CSS** (estilização)
- **Recharts** (gráficos)
- **Lucide React** (ícones)

## Como rodar localmente

```bash
# 1. Instalar dependências
npm install

# 2. Rodar em modo desenvolvimento
npm run dev

# 3. Abrir no navegador
# http://localhost:5173
```

## Como fazer build para produção

```bash
npm run build
# Arquivos gerados em /dist
```

## Estrutura

```
runcommerce-dashboard/
├── src/
│   ├── Dashboard.tsx   # Componente principal com todos os dados e UI
│   ├── main.tsx        # Entry point React
│   └── index.css       # Tailwind CSS
├── index.html
├── package.json
├── vite.config.ts
├── tailwind.config.js
└── tsconfig.json
```

## Atualizar dados

Todos os dados do dashboard estão no topo de `src/Dashboard.tsx`:

- `dadosSemanais` — faturamento, conversão, TKM e pedidos por semana
- `dadosMes` — totais acumulados, metas e projeções do mês
- `totais` — acumulado para o card de resumo

---

*run.commerce by Scheffer Consult — 2026*
