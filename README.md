# Exercícios de HTML e CSS

Este repositório contém uma série de exercícios para praticar **HTML** e **CSS** com foco em propriedades de **Flexbox**. Cada exercício explora diferentes conceitos de layout responsivo e estilização com CSS.

## Índice
1. [Exercício 1](https://github.com/iampabllo/exercicios/tree/main/display-flex/exec001)
2. [Exercício 2](https://github.com/iampabllo/exercicios/tree/main/display-flex/exec002)
3. [Exercício 3](https://github.com/iampabllo/exercicios/tree/main/display-flex/exec003)
4. [Exercício 4](https://github.com/iampabllo/exercicios/tree/main/display-flex/exec004)

---

### Exercício 1: Alinhamento Horizontal de Itens
**Objetivo:** Criar uma caixa com três elementos (`<div>`) centralizados horizontalmente usando Flexbox.

**CSS Principal:**
```css
.container {
  display: flex;
  justify-content: center;
}
```

**Desafio Adicional:** Experimente outros valores para `justify-content`, como `space-around`, `space-between`, e observe o comportamento.

---

### Exercício 2: Alinhamento Vertical de Itens
**Objetivo:** Colocar três elementos dentro de um contêiner e alinhá-los verticalmente ao centro da caixa.

**CSS Principal:**
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

**Desafio Adicional:** Altere o valor de `align-items` para `flex-start` ou `flex-end` e observe as mudanças.

---

### Exercício 3: Layout em Coluna com Flexbox
**Objetivo:** Organizar três caixas (`<div>`) em uma coluna dentro do contêiner usando `flex-direction: column`.

**CSS Principal:**
```css
.container {
  display: flex;
  flex-direction: column;
}
```

**Desafio Adicional:** Altere `flex-direction` para `row` para entender como o layout muda.

---

### Exercício 4: Distribuindo Espaços com Flexbox
**Objetivo:** Usar `flex-grow` para fazer com que as caixas cresçam para ocupar o espaço disponível.

**CSS Principal:**
```css
.box {
  flex-grow: 1;
}
```

**Desafio Adicional:** Defina valores diferentes para `flex-grow` em cada caixa para ver o efeito.

---

### Exercício 5: Flexbox Responsivo
**Objetivo:** Criar um layout de galeria de imagens que se ajusta automaticamente à largura da tela, usando `flex-wrap`.

**CSS Principal:**
```css
.container {
  display: flex;
  flex-wrap: wrap;
}
```

**Desafio Adicional:** Redimensione a janela do navegador para ver como os itens se reorganizam automaticamente.

---
