---
title: 13. Exercício - Adicionando um botão
parent: Aula 02 - Criando sua primeira app
nav_order: 13
---

## Exercício - Adicionando um botão

Neste exercício, você adicionará um botão ao seu aplicativo da mesma forma que fizemos no vídeo.

### 1. Copie o código XML do layout abaixo, caso ainda não o tenha feito:

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="30sp"
        android:text="1" />

</LinearLayout>
```
### 2. Adicione outra tag XML para o botão:

Certifique-se de definir o texto como “Roll” extraindo a string para recursos e alinhando o botão horizontalmente em direção ao centro da tela.

```xml
<Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:text="@string/roll" />
```

### 3. Posicione todas as views dentro do LinearLayout:

Para fazer isso, defina a orientação do LinearLayout como vertical e use *layout_gravity*  para alinhar os elementos de forma que fiquem centralizados conforme o esperado.

```xml
android:layout_gravity="center_vertical"
android:orientation="vertical"
```

Se quiser começar nesta etapa, você pode baixar este código de exercício em: [Step.01-Exercise-Add-the-button](https://github.com/udacity/andfun-kotlin-dice-roller/archive/Step.01-Exercise-Adding-the-button.zip).

Você encontrará muitos comentários **//TODO** para ajudá-lo a concluir este exercício e, se tiver dúvidas, volte e assista ao vídeo novamente.

Assim que terminar, você pode comparar sua solução com a solução que fornecemos aqui [Step.01-Solution-Adicionando-o-botão](https://github.com/udacity/andfun-kotlin-dice-roller/tree/Step.01-Solution-Adding-the-button) ou usando este [git diff](https://github.com/udacity/andfun-kotlin-dice-roller/compare/Step.01-Exercise-Adding-the-button...Step.01-Solution-Adding-the-button).


<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](14-conectando-o-botao){: .btn }</i>
</span>
