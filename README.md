# Mercado App (PWA Offline)

App de lista de compras com foco em uso no celular, **sem banco de dados online**.

## O que foi implementado

- Persistência local com **IndexedDB** (fallback para localStorage).
- PWA instalável com Service Worker e Manifest.
- Funciona offline após o primeiro carregamento.
- Swipe para remover itens da lista.
- Scanner de código de barras com `BarcodeDetector` (quando suportado).
- Catálogo com categorias e criação de produtos personalizados.
- Ordenação inteligente por corredor.
- Lista de essenciais com 1 toque.
- Relatório com previsão de orçamento do próximo mês.

## Publicar no GitHub Pages

1. Suba o repositório para o GitHub.
2. Em **Settings > Pages**, escolha branch `main` (ou a branch desejada) e pasta `/root`.
3. Acesse a URL gerada.

## Instalar no Android

1. Abra a URL no Chrome Android.
2. Toque em **Instalar app** (ou menu `⋮ > Instalar app`).
3. O app ficará salvo no celular e continuará funcionando offline.

> Dica: o armazenamento é local ao dispositivo. Para backup, use sincronização do navegador/sistema ou exporte o projeto com uma camada nativa (Capacitor) se quiser APK no futuro.
