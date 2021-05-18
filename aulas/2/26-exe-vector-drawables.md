---
title: 26. Execício -  Drawable vetoriais
parent: Aula 02 - Criando sua primeira app
nav_order: 26
youtubeId: kQ806dFpld8
---

## Exercício - Drawable vetoriais

{% include youtubePlayer.html id=page.youtubeId %}

Agora é a sua vez de completar este exercício.

### 1. Ative o uso da biblioteca de suporte para desenhos de vetores no arquivo build.gradle (módulo app):

```kotlin
vectorDrawables.useSupportLibrary = true
```
### 2. Use app:srcCompat na tag image no arquivo de layout:

```xml
app:srcCompat="@drawble/empty_dice"
```

### 3. Você também precisará adicionar o namespace na raiz do layout:

```xml
xmlns:app="http://schemas.android.com/apk/res-auto"
```

Se você quiser começar nesta etapa, você pode baixar este código de exercício aqui: [Step.06-Exercise-Use-Vector-Drawable-Compat](https://github.com/udacity/andfun-kotlin-dice-roller/archive/Step.06-Exercise-Use-Vector-Drawable-Compat.zip).

Você encontrará muitos comentários de **//TODO** para ajudá-lo a concluir este exercício e, se você ficar preso, volte e assista ao vídeo novamente.

Quando terminar, você pode verificar sua solução contra a solução que fornecemos aqui [Step.06-Solution-Use-Vector-Drawable-Compat](https://github.com/udacity/andfun-kotlin-dice-roller/tree/Step.06-Solution-Use-Vector-Drawable-Compat) ou usando este [git diff](https://github.com/udacity/andfun-kotlin-dice-roller/compare/Step.06-Exercise-Use-Vector-Drawable-Compat...Step.06-Solution-Use-Vector-Drawable-Compat).


Se você está tentando decidir quais versões para apoiar, você pode conferir:

- O diálogo "Ajuda-me Escolher", que é mostrado quando você está configurando o Andorid Studio
- As [notas de lançamento](https://developer.android.com/about/versions/pie/) de cada versão
- [Painel de versão](https://developer.android.com/about/dashboards/) da plataforma


<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](27-revisao){: .btn }</i>
</span>
