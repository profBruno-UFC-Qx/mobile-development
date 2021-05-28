---
title: 11. Exercício - Hello World
parent: Aula 02 - Criando sua primeira app
nav_order: 11
youtubeId: bEYacJAHO4E
---

## Exercício - Hello World

{% include youtubePlayer.html id=page.youtubeId %}

Agora é sua vez de concluir este exercício.

Neste exercício, você modificará o texto mostrado na tela para  *Hello Android* .

### 1. Abra o arquivo de layout MainActivity e altere o “Hello World!” para “Hello Android!”:

Você pode fazer isso alterando o atributo de texto no XML:

```xml
android:text="Hello Android"
```

Nenhuma outra mudança é necessária! Como este exercício foi rápido, não precisaremos mexer em código Kotlin. 
Mas seu código final *activity_main.xml* deve ser semelhante a:

```xml
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello Android!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```


<div style="text-align: center">
<img alt="hello-android" src="/assets/images/helloandroid.png" width="228px"/>
</div>

<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](12-adicionando-um-botao){: .btn }</i>
</span>
