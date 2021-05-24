---
title: 12. Scope functions
parent: Aula 03 - Fundamentos básicos de Kotlin
nav_order: 12
youtubeId: dIcyOrPC1Jk
---

## Extension functions

{% include youtubePlayer.html id=page.youtubeId %}

### Resumo das diferenças das Scope Functions

| Função      | Referência ao objeto | Valor de retorno           | É extension function ? |
|:------------|:---------------------|:---------------------------|:-----------------------|
| let         | it                   | Resultado da função lambda | Sim                    |
| run         | this                 | Resultado da função lambda | Sim                    |
| with        | this                 | Resultado da função lambda | Não                    |
| apply       | this                 | Objeto dono do contexto    | Sim                    |
| with        | this                 | Objeto dono do             | Sim                    |



Adaptado de: [Documentação oficial sobre Scope functions](https://kotlinlang.org/docs/scope-functions.html#function-selection)

<span class="fs-3 float-right">
<i class="fas fa-download">[Próxima aulas](tarefa-de-casa){: .btn }</i>
</span>
