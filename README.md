# Evento de Propagação e Evento de Captura - Exemplo

### O que é evento de propagação ?
Evento de propagação determina a ordem em que os elementos recebem os eventos. Por padrão sempre utilizamos o evento de propagação ascendente o qual ocorre do elemento pai para o elemento Document, porém existe outro tipo de evento de propagação que é conhecido como descendente  ou evento de captura o qual ocorre do elemento filho para o elemento Document. 

A especificação de qual tipo de evento estamos usando se encontra no 3º argumento do método addEventListener(), o "useCapture". Esse 3º argumento pode receber um true ou false, dizendo desta forma por qual ordem os elementos irão receber o evento: por propagação ou por captura.

### Exemplo desenvolvido:
Criação de duas divs e um botão

### Tecnologias Web utilizadas para  o desenvolvimento: 
- 📄 HTML: conteúdo
- 🛠 Javascript: lógica e interação

### Conteúdo aplicado:
- Evento de Propagação
- Método de captura: querySelector()
- Método de evento: addEventListener()
- Argumento: useCapture
