# Button

### Implementando
Veja abaixo alguns exemplos de código (snippets) de como implementar o componente de acordo com as diversas variações, estados e eventos. 
Você pode conferir mais detalhes e possibilidades através das tabelas de propriedades e eventos no fim da página:

#### Primary

```xml
<com.lego.button.ButtonPrimary
   android:text="Button Primary"
   app:icon="ic_hearth"/>
```

```kotlin
val primaryButton = ButtonPrimary()
primaryButton.text = "Button Primary"
primaryButton.icon = "ic_hearth"
```

#### Secondary

```xml
<com.lego.button.ButtonSecondary
   android:text="Button Secondary"
   app:icon="ic_hearth"/>
```

```kotlin
val secondaryButton = ButtonSecondary()
secondaryButton.text = "Button Secondary"
secondaryButton.icon = "ic_hearth"
```

### Propriedades

| Nome    | Descrição                                                         | Tipo      | Obrigatório |
|---------|-------------------------------------------------------------------|-----------|-------------|
| text    | Define o texto a ser exibido no botão                             |   String  |    Sim      |
| icon.   | Define o ícone a ser mostrado do lado direito do botão.           |   String  |    Não      |
