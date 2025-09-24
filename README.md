# 🛠️ Refatoração de Código

> Seguindo o guia de estudos na [Alura]("alura.com.br") e exemplos práticos sobre **refatoração** consegui desenvolver novas habilidades para desenvolver um código limpo e sem o tão famoso "Bad smell".

---

# O que aprendi: 

## 📚 O que é Refatoração?
Refatoração é o **processo de melhorar a estrutura interna do código** sem mudar sua funcionalidade externa.  
O objetivo é tornar o código **mais legível, simples, eficiente e fácil de manter**.

---

## 🎯 Benefícios
- ✅ **Legibilidade**: Código mais claro para outros desenvolvedores (e para você no futuro).
- ✅ **Manutenibilidade**: Facilita correções e adição de novas funcionalidades.
- ✅ **Redução de Bugs**: Estrutura mais organizada diminui erros ocultos.
- ✅ **Performance do time**: Equipes trabalham mais rápido com código limpo.

---

## ⚠️ Code Smells (Maus Cheiros)
Sinais de que o código precisa de refatoração:
- **Método muito grande**: Faz mais de uma coisa.
- **Duplicação de código**: Mesma lógica repetida em vários lugares.
- **Nomes ruins**: Variáveis ou métodos com nomes confusos.
- **Classe “Deus”**: Uma classe que faz de tudo.
- **Comentário excessivo**: Comentários que tentam explicar código mal escrito.

> 💡 *Code smell* não é bug, mas um alerta de que algo pode ser melhorado.

---

## 🔧 Técnicas Comuns
| Técnica | Descrição | Exemplo |
|--------|-----------|--------|
| **Extract Method** | Extrair parte de um método grande em um novo método | Melhorar clareza |
| **Rename Variable/Method** | Dar nomes mais significativos | `calc()` → `calculateDiscount()` |
| **Inline Variable** | Substituir variáveis temporárias desnecessárias | Remover intermediários |
| **Replace Magic Number** | Substituir números “mágicos” por constantes | `0.07` → `TAX_RATE` |
| **Move Method/Field** | Mover método ou atributo para a classe correta | Melhor coesão |

---

## 🧩 Princípios Relacionados
- **SOLID**: Princípios para design orientado a objetos.
- **DRY (Don't Repeat Yourself)**: Evite duplicação de código.
- **KISS (Keep It Simple, Stupid)**: Prefira soluções simples.

---

## ⚙️ Ferramentas de Apoio
- **IntelliJ IDEA / Eclipse / VSCode**: Atalhos para renomear, extrair métodos, mover classes.
- **SonarLint / SonarQube**: Identificam *code smells* automaticamente.
- **JUnit / Testes Automatizados**: Garantem que o comportamento não mudou.

---


Obrigado por ficar até aqui !!
Projeto desenvolvido parafins de estudo e desenvolvimento de novas habilidades.
