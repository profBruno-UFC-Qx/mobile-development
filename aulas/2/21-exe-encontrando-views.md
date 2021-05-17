---
title: 21. Exercício - Encontrando Views eficientemente
parent: Aula 02 - Criando sua primeira app
nav_order: 21
youtubeId: HqE27ULKdPg
---

## Exercício - Encontrando Views eficientemente

{% include youtubePlayer.html id=page.youtubeId %}

Aqui está informações adicionais sobre o tema da inicialização tardia (late init), se você estiver curioso: propriedades de [variáveis com inicialização tardia](https://kotlinlang.org/docs/reference/properties.html#late-initialized-properties-and-variables).

Agora é a sua vez de completar este exercício.

### 1. Use Latinit para extrair a variável de exibição de imagem:

```kotlin
lateinit var diceImage: ImageView
```

### 2. Inicialize a variável ImageView

```kotlin
diceImage = findViewById(R.id.dice_image)
```

Se você quiser começar nesta etapa, você pode baixar este código de exercício aqui: [Step.05-Exercise-Finding-Views-Efficiently.](https://github.com/udacity/andfun-kotlin-dice-roller/archive/Step.05-Exercise-Finding-Views-Efficiently.zip)

Você encontrará muitos comentários de **//TODO** para ajudá-lo a concluir este exercício e, se você ficar preso, volte e assista ao vídeo novamente.

Quando terminar, você pode verificar sua solução contra a solução que fornecemos aqui [Step.05-Solution-Finding-Views-Efficiently](https://github.com/udacity/andfun-kotlin-dice-roller/tree/Step.05-Solution-Finding-Views-Efficiently) ou usando este [git diff](https://github.com/udacity/andfun-kotlin-dice-roller/compare/Step.05-Exercise-Finding-Views-Efficiently...Step.05-Solution-Finding-Views-Efficiently).

<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](22-namespaces){: .btn }</i>
</span>
