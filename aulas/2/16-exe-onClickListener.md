---
title: 16. Exercício - onClickListener
parent: Aula 02 - Criando sua primeira app
nav_order: 16
youtubeId: FHmV52WtbNU
---

## Exercício - onClickListener

{% include youtubePlayer.html id=page.youtubeId %}

Neste exercício, você fará com que seu aplicativo mostre uma mensagem `Toast` sempre que o botão for clicado.

- [OnClickListener](https://developer.android.com/reference/android/view/View.OnClickListener)
- [Documentação do Toast](https://developer.android.com/guide/topics/ui/notifiers/toasts)

### 1. Certifique-se de ter concluído as etapas para findViewById:

Você precisará usar o `findViewById` para o botão, conforme descrito no último vídeo.

### 2. Defina o OnClickListener para o botão:

```kotlin
rollButton.setOnClickListener {

}
```
### 3. Faça o Toast:

Este código fará com que o rollButton mostre uma mensagem `Toast`.

```kotlin
rollButton.setOnClickListener {
    Toast.makeText(this, "button clicked", Toast.LENGTH_SHORT).show()
}
```

Se quiser começar nesta etapa, você pode baixar este código de exercício aqui: [Step.02-Exercise-OnClickListener](https://github.com/udacity/andfun-kotlin-dice-roller/archive/Step.02-Exercise-OnClickListener.zip).

Você encontrará muitos comentários **//TODO** para ajudá-lo a concluir este exercício e, se tiver dúvidas, volte e assista ao vídeo novamente.

Quando terminar, você pode comparar sua solução com a solução que fornecemos aqui [Step.02-Solution-OnClickListener](https://github.com/udacity/andfun-kotlin-dice-roller/tree/Step.02-Solution-OnClickListener) ou usando este [git diff](https://github.com/udacity/andfun-kotlin-dice-roller/compare/Step.02-Exercise-OnClickListener...Step.02-Solution-OnClickListener).

<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](17-exe-alterar-o-texto){: .btn }</i>
</span>
