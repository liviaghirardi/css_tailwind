# Projeto: Geometria Interativa com Tailwind CSS

Este projeto é uma aplicação web desenvolvida para demonstrar a criação e estilização de uma **Galeria de Figuras & Fórmulas Geométricas** utilizando o framework utility-first **Tailwind CSS**. A aplicação apresenta 10 formas geométricas planas e exibe suas respectivas fórmulas matemáticas de área e perímetro com uma interface moderna e responsiva.

---

## 📋 Requisitos do Projeto

1. **Inclusão do Tailwind CSS**: Configuração e carregamento do Tailwind CSS via CDN no cabeçalho do documento HTML.
2. **Layout Responsivo via Classes Utilitárias**: Organização da interface usando as classes nativas de Grid, Flexbox e espaçamento do Tailwind.
3. **Design System Integrado**: Uso da paleta de cores, tipografia e sombras padrão da biblioteca para uma UI consistente.
4. **Formas Geométricas Customizadas**: Estilização visual das 10 figuras geométricas utilizando classes do Tailwind e utilitários arbitrários (como `clip-path`).

---

## 📐 Figuras Geométricas Implementadas

A galeria aborda a representação visual e matemática de 10 figuras planas:

1. **Quadrado**: Estilizado com `w-32 h-32 bg-indigo-500 rounded-lg`.
2. **Círculo**: Modelado com `w-32 h-32 bg-emerald-500 rounded-full`.
3. **Retângulo**: Estruturado com `w-40 h-24 bg-amber-500 rounded-lg`.
4. **Elipse**: Definido com `w-40 h-24 bg-rose-500 rounded-full`.
5. **Losango**: Construído com rotação `w-28 h-28 bg-purple-500 rotate-45 rounded-sm`.
6. **Triângulo**: Recortado via classe arbitrária `[clip-path:polygon(50%_0%,0%_100%,100%_100%)]`.
7. **Trapézio**: Criado com `[clip-path:polygon(20%_0%,80%_0%,100%_100%,0%_100%)]`.
8. **Paralelogramo**: Aplicado efeito de inclinação com `-skew-x-12`.
9. **Pentágono**: Modelado via recorte geométrico de 5 vértices.
10. **Hexágono**: Construído com polígono regular de 6 vértices.

---

## 🛠️ Recursos do Tailwind CSS Utilizados

- **Grid System**: `grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6` para um layout responsivo automático.
- **Flexbox**: `flex items-center justify-between` e `flex flex-col` no cabeçalho e nos cards.
- **Efeitos e Microinterações**: `hover:-translate-y-1 transition-all duration-200 shadow-md hover:shadow-xl` para interatividade nos cards.
- **Valores Arbitrários**: Uso da sintaxe `[...]` do Tailwind para aplicar regras de `clip-path` sem a necessidade de arquivos CSS adicionais.

---

## 📱 Responsividade
Graças aos modificadores de breakpoint do Tailwind (`sm:`, `md:`, `lg:`), o layout se adapta perfeitamente a dispositivos móveis, tablets e telas widescreen.

---

## 📂 Como Executar o Projeto
1. Clone o repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` em qualquer navegador web (não requer etapas de build para visualização).
