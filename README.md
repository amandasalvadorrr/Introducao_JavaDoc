# 📘 Introdução ao JavaDoc

O JavaDoc é a ferramenta de documentação oficial do Java.  
Ele permite gerar páginas HTML a partir de comentários estruturados no código.

---

## O que deve ser documentado?

- Objetivo da classe  
- O que cada método faz  
- Parâmetros  
- Valor de retorno  
- Exceções que podem ocorrer  
- Quando usar ou não usar

---

## Como funciona o JavaDoc?

O JavaDoc é escrito usando o formato:
/**
Comentário em JavaDoc
*/


---

## Tags do JavaDoc

### Tags Essenciais
- `@param` — descreve cada parâmetro do método  
- `@return` — descreve o que o método retorna  
- `@throws` / `@exception` — indica exceções lançadas  
- `@author` — autor  
- `@version` — versão da classe  
- `@see` — referência para outra classe/método  
- `@deprecated` — indica que algo está obsoleto  

---

### Tags Intermediárias
- `@since` — a partir de qual versão o recurso existe  
- `@serial` — usado em campos serializáveis  
- `@link` — cria links internos na documentação  

---

## Como usar na prática?

Basta escrever os comentários acima dos métodos ou classes usando `/** */` e adicionar as tags conforme necessário.  
Ferramentas como o comando `javadoc` conseguem gerar automaticamente documentos HTML baseados nesses comentários.

---
