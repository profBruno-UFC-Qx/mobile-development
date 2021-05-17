---
title: 17. Exercício - Alterar o texto
parent: Aula 02 - Criando sua primeira app
nav_order: 17
youtubeId: yEaVTrMQTsY
---

## Exercício - Alterar o texto

{% include youtubePlayer.html id=page.youtubeId %}

Neste exercício, você fará com que seu aplicativo mostre um número aleatório na `TextView result_text`.

### 1. Atribua um id a TextView no layout:

```xml
android:id="@+id/result_text"
```

### 2. Remova o Toast e crie um método chamado rollDice:

Você pode fazer isso adicionando o seguinte:

```kotlin
rollButton.setOnClickListener {
    rollDice()
}
```

E então, usando o atalho do teclado, você pode gerar o método no AndroidStudio:

Windows / Linux: Alt + Enter

Mac: Option + Enter

### 3. Escreva com o método rollDice para obter um número aleatório entre 1 e 6:

```kotlin
val randomInt = Random().nextInt(6) + 1
```

### 4. Use findViewById para obter uma referência para TextView e atribua-a a uma variável imutável chamada resultText:

```kotlin
val resultText: TextView = findViewById(R.id.result_text)
```

### 5. Finalmente, defina o valor aleatório que você obteve acima como o texto de TextView:

```kotlin
resultText.text = randomInt.toString()
```

Se quiser começar nesta etapa, você pode baixar este código de exercício aqui: [Step.03-Exercise-Rolling-the-dice](https://github.com/udacity/andfun-kotlin-dice-roller/archive/Step.03-Exercise-Rolling-the-dice.zip).

Você encontrará muitos comentários **//TODO** para ajudá-lo a concluir este exercício e, se tiver dúvidas, volte e assista ao vídeo novamente.

Quando terminar, você pode comparar sua solução com a solução que fornecemos aqui [Step.03-Solution-Rolling-the-dice](https://github.com/udacity/andfun-kotlin-dice-roller/tree/Step.03-Solution-Rolling-the-dice) ou usando este [git diff](https://github.com/udacity/andfun-kotlin-dice-roller/compare/Step.03-Exercise-Rolling-the-dice...Step.03-Solution-Rolling-the-dice).

<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](18-imagens-de-um-dado){: .btn }</i>
</span>
