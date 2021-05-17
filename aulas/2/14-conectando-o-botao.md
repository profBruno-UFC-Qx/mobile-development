---
title: 14. Conectando o botão
parent: Aula 02 - Criando sua primeira app
nav_order: 14
youtubeId: 41tQ_-M58bM
---

## Conectando um botão

{% include youtubePlayer.html id=page.youtubeId %}

### Uma observação sobre o recurso de vinculação de visualização (Android Studio 3.6+)

Desde o lançamento deste curso, um novo recurso, **view binding**, foi introduzido e está disponível no Android Studio 3.6 e superiores. 
Não usamos view binding porque foi lançado após o curso, mas é um recurso que você deve conhecer.

[View Binding](https://developer.android.com/topic/libraries/view-binding) substitui `findViewById`. ViewBinding gera um objeto de ligação para cada layout XML. 
Você usa este objeto de ligação para fazer referência a `views`, usando seus IDs de recurso como o nome:

```java
// Creating a binding object for the main_activity.xml layout
binding = ActivityMainBinding.inflate(layoutInflater)

// Referencing a view with the ID roll_button
binding.rollButton
```

Usar **view binding** trás os seguintes benefícios em relação a `findViewById`:

**Segurança de tipo** - `findViewById` requer que você especifique o tipo de `view` que você espera que seja retornado. 
Por exemplo, se você acidentalmente especificar que espera que um `ImageButton` seja retornado quando na realidade o tipo for um `Button`, você obterá uma [ClassCastException](https://developer.android.com/reference/java/lang/ClassCastException). A **view binding** protege você desse tipo de erro porque a view é uma propriedade corretamente tipada.

**Segurança contra null (Null Safety)** - `findViewById` espera um parâmetro inteiro, que deve ser o ID de recurso de uma visualização. 
É possível, entretanto, passar qualquer número inteiro como parâmetro, incluindo números inteiros não relacionados e ids de views inválidos. 
Se você fornecer um número inteiro que não corresponda a um id de recurso de view no layout, `findViewById` retorna `null` e pode causar um `NullPointerException`.
A **view binding** é segura contra `null``  porque você referência views diretamente e não os seus IDs.

Para saber mais sobre como usar **view binding** em seu aplicativo, verifique a documentação sobre [View Binding](https://d.android.com/topic/libraries/view-binding) e a parte [Accessing Views](https://youtu.be/Qxj2eBmXLHg?t=444) parte da [What's new in Architecture Components - Google I/O'19](https://www.youtube.com/watch?v=Qxj2eBmXLHg).


<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](15-exe-findViewById){: .btn }</i>
</span>
