---
title: 20. Exercício - Adicionando um ImageView
parent: Aula 02 - Criando sua primeira app
nav_order: 20
youtubeId: NRNeiBv5FIs
---

## Exercício - Adicionando um ImageView

{% include youtubePlayer.html id=page.youtubeId %}

Neste exercício, você substituirá o TextView por um ImageView que mostrará o direito elaborável com base no número aleatório.

### 1. Adicione as imagens de dados à pasta drawable

Adicione o arquivo de [imagens do dado](https://github.com/udacity/andfun-kotlin-dice-roller/raw/master/DiceImages.zip) como explicado no [vídeo anterior](http://localhost:4000/aulas/2/19-exe-adicionando-imagens-de-recursos.html).

### 2. Substitua o TextView pelo ImageView e atribua vazio_dice a ele:

```xml
<ImageView
        android:id="@+id/dice_image"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:src="@drawable/empty_dice" />
```

### 3. Substitua a referência ao TextView com a do ImageView:

```kotlin
val diceImage: ImageView = findViewById(R.id.dice_image)
```

### 4. Escolha o recurso drawable certo com base no valor do randomint:

```kotlin
val drawableResource = when (randomInt) {
            1 -> R.drawable.dice_1
            2 -> R.drawable.dice_2
            3 -> R.drawable.dice_3
            4 -> R.drawable.dice_4
            5 -> R.drawable.dice_5
            else -> R.drawable.dice_6
        }
```

### 5. Finalmente, atribua o drawableResource ao ImageResource no diceImage:

```kotlin
diceImage.setImageResource(drawableResource)
```

Se você quiser começar nesta etapa, você pode baixar este código de exercício aqui: [Step.04-Exercise-Adding-the-ImageView](https://github.com/udacity/andfun-kotlin-dice-roller/archive/Step.04-Exercise-Adding-the-ImageView.zip).

Você encontrará muitos comentários de **//TODO** para ajudá-lo a concluir este exercício e, se você ficar preso, volte e assista ao vídeo novamente.

Quando terminar, você pode verificar sua solução contra a solução que fornecemos aqui [Step.04-Solution-Adding-the-ImageView](https://github.com/udacity/andfun-kotlin-dice-roller/tree/Step.04-Solution-Adding-the-ImageView) ou usando este [git diff](https://github.com/udacity/andfun-kotlin-dice-roller/compare/Step.04-Exercise-Adding-the-ImageView...Step.04-Solution-Adding-the-ImageView).

<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](21-exe-encontrando-views){: .btn }</i>
</span>
