---
title: 15. Exercício - findViewById
parent: Aula 02 - Criando sua primeira app
nav_order: 15
youtubeId: 9Cbv77tMQQg
---

## Exercício - findViewById

{% include youtubePlayer.html id=page.youtubeId %}

Agora é a sua vez de concluir este exercício sozinho.

Neste exercício, você usará `findViewById` para obter uma referência ao botão.

### 1. Defina o id do botão no arquivo de layout activity_main.xml:

```xml
android:id="@+id/roll_button"
```

### 2. Use findViewById para obter uma referência ao botão e atribuí-lo a uma variável imutável chamada rollButton:
```kotlin
val rollButton: Button = findViewById(R.id.roll_button)
```

### 3. (Opcional) Modifique dinamicamente a visualização do botão:

```kotlin
rollButton.text = "Let's Roll"
```
<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](16-exe-onClickListener){: .btn }</i>
</span>
