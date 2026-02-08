# Formulário Lindão ✨

Formulários podem até parecer algo complicado à primeira vista, mas a verdade é que **não são nenhum bicho de sete cabeças**.

Neste projeto, você vai aprender **como criar um formulário do zero** e deixá-lo *lindão*, utilizando **HTML e CSS** para estruturar e estilizar, trazendo uma aparência mais profissional ao layout.

---

## 🧩 Iniciando um formulário

Quando pensamos na construção de um formulário, geralmente ele precisa conter alguns campos básicos, como:

- E-mail  
- Seleção de um curso da grade escolar  
- Nível de conhecimento  
- Campo para comentários  
- Botão para salvar/enviar as informações  

Esses campos surgem de necessidades reais. É exatamente por isso que os formulários são tão utilizados: eles aparecem em **diversos formatos e contextos**, sempre com o objetivo de coletar informações de forma organizada e atender a um modelo específico.

Antes de começar a codar, desenhar a ideia ajuda muito. Isso facilita a visualização do fluxo e o entendimento do passo a passo até chegar na solução final.  
Neste projeto, utilizamos um **modelo visual de formulário como referência**.

---

## 🛠️ Construção com HTML e CSS

A construção foi feita utilizando uma IDE, no caso o **Visual Studio Code**.

Para acompanhar o projeto, você pode:

- Criar um arquivo `index.html` para a estrutura HTML  
- Criar um arquivo `style.css` para a estilização  
- Ou, se preferir, usar o **CodePen** para testar tudo online  

---

## 🧠 Entendendo a estrutura de um formulário HTML

Abaixo está a explicação dos principais elementos utilizados neste formulário.

---

### `<form>` — o contêiner principal

O `<form>` é o elemento mais externo do formulário.  
Ele funciona como um grande contêiner, responsável por agrupar todos os campos e permitir o envio das informações.

📌 Tudo o que será enviado precisa estar dentro dessa tag.

---

### `<fieldset>` — agrupando informações relacionadas

O `<fieldset>` é usado para agrupar campos que fazem parte de um mesmo contexto, deixando o formulário mais organizado visualmente e semanticamente.

Além disso, ele melhora a acessibilidade, ajudando leitores de tela a entenderem melhor a estrutura do formulário.

---

### `<legend>` — o título do grupo

O `<legend>` funciona como um título do `fieldset`.  
Neste projeto, ele aparece como o texto **"Formulário"**, deixando claro para o usuário o que aquele conjunto de campos representa.

---

### `<label>` — descrevendo cada campo

O `<label>` é responsável por identificar e descrever o campo que o usuário vai preencher, como **Email**, **Curso** ou **Nível de conhecimento**.

Usar `label` é uma boa prática porque:

- Melhora a acessibilidade  
- Aumenta a área clicável do campo  
- Deixa o formulário mais claro e intuitivo  

---

### `<input>` — campos de entrada de dados

O `<input>` é um dos elementos mais versáteis do formulário.  
Neste projeto, ele aparece em diferentes variações:

- `type="email"` → para capturar e-mails  
- `type="radio"` → para selecionar uma única opção  
- `type="checkbox"` → para marcar várias opções  
- `type="submit"` → para enviar o formulário  

Cada tipo define **como o usuário interage** com o campo.

---

### `<select>` — escolhendo uma opção

O `<select>` é utilizado quando o usuário precisa escolher uma opção dentro de uma lista, como no campo de curso.

Ele ajuda a:

- Evitar erros de digitação  
- Padronizar respostas  
- Melhorar a experiência do usuário  

---

### `<textarea>` — textos maiores

O `<textarea>` é ideal para campos de texto mais longos, como comentários ou mensagens.

Diferente do `<input>`, ele possui **tag de abertura e fechamento**, permitindo definir melhor o espaço para escrita.

---

### `<input type="submit">` — enviando o formulário

Por fim, temos o botão de envio.  
Ele é o responsável por **disparar a ação do formulário**, enviando os dados preenchidos pelo usuário.

---

## 🔗 Links do projeto

- **Código-fonte:**  
  https://github.com/obayo-devs/criandoform  

- **Projeto no ar (GitHub Pages):**  
  https://obayo-devs.github.io/criandoform/  

---

## ✨ Autoria

Projeto desenvolvido por **Joselaine Romão | Obayo** 💜  

