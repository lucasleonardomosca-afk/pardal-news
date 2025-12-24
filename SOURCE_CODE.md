# Código-Fonte do Pardal - Regional Intelligence

## Localização do Código Completo

O código-fonte completo da aplicação Pardal está disponível no Google AI Studio:

**URL:** https://aistudio.google.com/apps/drive/1HCswQBaOYAcpXJQyeN65kxENsivlPQd-

## Estrutura da Aplicação

### Arquivos Principais

#### 1. **App.tsx** (Componente React Principal)
- Contém toda a lógica da aplicação
- Gerenciamento de estado (view, activeArticle, etc.)
- Mock data completo com artigos regionais
- Componentes:
  - Header (Pardal branding)
  - Threshold (entrada editorial)
  - HomePage (grid de artigos)
  - ArticlePage (visualização completa)
  - Footer

#### 2. **index.tsx**
- Entry point da aplicação React
- Renderização do componente App

#### 3. **index.html**
- Template HTML base
- Carregamento de fontes (Crimson Pro, Inter)
- Configuração de viewport e meta tags

#### 4. **metadata.json**
- Metadados do Google AI Studio
- Configurações de aplicação

### Pasta documentation/

Contém 25+ arquivos de documentação Markdown detalhando:
- CHARTER.md - Carta editorial
- EDITORIAL_GOVERNANCE.md - Governança editorial
- EDITORIAL_VOICE.md - Tom e voz editorial
- ETHICS.md - Princípios éticos
- FORMATS.md - Formatos de conteúdo
- TAXONOMY_REGIONAL.md - Taxonomia regional
- E muitos outros...

## Arquitetura

### Stack Tecnológico
- **Framework:** React 18+ (TypeScript)
- **Styling:** Tailwind CSS
- **Backend (futuro):** Firebase (Firestore, Auth, Storage)
- **Build:** Vite

### Dados Mock (Em App.tsx)

A aplicação atualmente usa dados mock estruturados representando:

**Cidades Cobertas:**
- São João da Boa Vista
- Mococa  
- São José do Rio Pardo
- Casa Branca

**Categorias:**
- Poder (Politics)
- Economia (Economy)
- Agrotech (The Harvest)
- Regional
- Global

### Tipos de Artigo
```typescript
type ArticleFormat = 'threshold' | 'edition' | 'long-form' | 'analytical' | 'note' | 'signal' | 'reflection' | 'patronage';
```

## Como Acessar o Código

1. Acesse o link do Google AI Studio acima
2. Clique na aba "Code"
3. Arquivos disponíveis:
   - App.tsx (código completo)
   - index.tsx
   - index.html
   - metadata.json
   - documentation/ (pasta com 25+ arquivos MD)

## Próximos Passos

Para implementar localmente:

1. Copiar arquivos do Google AI Studio
2. Configurar projeto Vite + React + TypeScript
3. Instalar dependências (React, Tailwind)
4. Configurar Firebase (quando necessário)

## Contato

Email: lucasleonardomosca@gmail.com
