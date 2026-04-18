# Foxtable Ultra — Documentação (README)

## Visão Geral
Foxtable Ultra é uma aplicação web para criação, edição e gerenciamento de gráficos interativos utilizando a biblioteca Chart.js. O sistema permite criar múltiplos gráficos, editar seus dados em tempo real, aplicar estilos visuais, exportar imagens e salvar projetos.

---

## Estrutura da Interface

### Topbar
Barra superior contendo:
- Nome da aplicação
- Campo de busca para filtrar gráficos pelo título

### Sidebar
Painel lateral esquerdo:
- Botão para criar novo gráfico
- Lista de gráficos existentes
- Seleção de gráfico ativo

### Workspace
Área central:
- Exibição do gráfico atual
- Título do gráfico renderizado acima do canvas

### Properties
Painel lateral direito:
- Edição das propriedades do gráfico selecionado
- Controles de dados, tipo, estilo e ações

---

## Estrutura de Dados

Cada gráfico é armazenado como um objeto dentro do array `graficos`:
