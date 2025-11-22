# 2. Markdown Básico: A Linguagem do README

O **Markdown** é uma linguagem de marcação simples que permite formatar texto usando símbolos fáceis de digitar. É a linguagem padrão para escrever `README.md`.

Aqui estão os comandos essenciais que você precisa para criar um `README` bem estruturado:

## 1. Títulos (Headers)

Use o símbolo `#` para criar títulos. Quanto mais `#`, menor o título.

| Comando | Resultado | Uso |
| :--- | :--- | :--- |
| `# Título Principal` | **<h1>Título Principal</h1>** | Nome do Projeto ou do Perfil. |
| `## Seção Importante` | **<h2>Seção Importante</h2>** | Visão Geral, Instalação, Contato. |
| `### Subseção` | **<h3>Subseção</h3>** | Pré-requisitos, Passo 1, Passo 2. |

## 2. Ênfase no Texto

Use asteriscos (`*`) ou sublinhados (`_`) para dar destaque.

| Comando | Resultado |
| :--- | :--- |
| `**Negrito**` ou `__Negrito__` | **Negrito** |
| `*Itálico*` ou `_Itálico_` | *Itálico* |
| `***Negrito e Itálico***` | ***Negrito e Itálico*** |

## 3. Listas

Listas tornam as instruções e os itens mais fáceis de ler.

### Lista Não Ordenada (Bullet Points)

Use `*`, `-` ou `+` seguido de um espaço.

```markdown
* Item 1
* Item 2
  - Subitem A
  - Subitem B
```

### Lista Ordenada (Numeração)

Use números seguidos de um ponto e um espaço.

```markdown
1. Primeiro Passo
2. Segundo Passo
3. Terceiro Passo
```

## 4. Links e Imagens

### Links

Use colchetes para o texto e parênteses para o endereço.

```markdown
[Texto que aparece no link](https://www.endereco.com)
```

### Imagens

É igual ao link, mas com um ponto de exclamação (`!`) na frente.

```markdown
![Texto Alternativo da Imagem](link-para-a-imagem.png)
```

## 5. Blocos de Código

Use blocos de código para mostrar comandos ou trechos de código.

### Código Inline

Use uma crase (`` ` ``) para destacar um comando no meio do texto.

*Exemplo: Use o comando `git clone` para baixar o projeto.*

### Bloco de Código

Use três crases (`` ``` ``) no início e no fim. Você pode indicar a linguagem para o GitHub colorir o código (Syntax Highlighting).

```markdown
```javascript
// Exemplo de código JavaScript
function hello() {
  console.log("Olá, mundo!");
}
```
```

**Próximo Passo:** Agora que você sabe o básico do Markdown, vamos aplicá-lo na prática! Vá para o **Guia 3: README de Perfil**.
