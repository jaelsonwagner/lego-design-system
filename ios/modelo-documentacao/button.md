# Button

### Implementando
Veja abaixo alguns exemplos de código (snippets) de como implementar o componente de acordo com as diversas variações, estados e eventos. 
Você pode conferir mais detalhes e possibilidades através das tabelas de propriedades e eventos no fim da página:

#### Primary

```swift
let button = Button(theme: Button())

button.render(.title("Button Primary"))
```

#### Secondary

```swift
let button = Button(theme: ButtonSecondary())

button.render(.title("Button Secondary"))
```

### Disabled

```swift
//enabled
button.render(.enabled(true))

//disabled
button.render(.enabled(false))
```

### Propriedades

| Nome    | Descrição                                                         | Tipo      | Obrigatório |
|---------|-------------------------------------------------------------------|-----------|-------------|
| text    | Define o texto a ser exibido no botão                             |   String  |    Sim      |
| icon.   | Define o ícone a ser mostrado do lado direito do botão.           |   String  |    Não      |
