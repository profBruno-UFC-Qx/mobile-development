---
title: Projeto Final
has_children: true
has_toc: true
nav_order: 23
prazo_proposta: 10/10/2025
prazo_telas: A Definir
prazo_func: A Definir
prazo_final: 11/01/2026
---

# Projeto Final

- [Projeto Final](#projeto-final)
  - [🎯 Objetivos de Aprendizagem ](#-objetivos-de-aprendizagem-)
  - [✅ Requisitos mínimos ](#-requisitos-mínimos-)
  - [⭐ Funcionalidades Bônus (para pontuação extra)](#-funcionalidades-bônus-para-pontuação-extra)
    - [⚠️ Atenção](#️-atenção)
  - [📊 Critérios de avaliação ](#-critérios-de-avaliação-)
  - [📅 Entregas](#-entregas)
    - [🗣️ Apresentação do trabalho ](#️-apresentação-do-trabalho-)



---

## 🎯 Objetivos de Aprendizagem <a name="obj"></a>

O projeto final será desenvolvido em dupla e consiste na criação de um aplicativo Android completo utilizando Kotlin e Jetpack Compose. O objetivo é integrar todos os conceitos aprendidos durante a disciplina em um produto funcional, com foco em boas práticas de desenvolvimento, experiência do usuário e qualidade de código.



- Planejar e desenvolver um aplicativo móvel aplicando arquitetura MVVM.
- Utilizar Jetpack Compose para construção de interfaces modernas e responsivas.
- Implementar persistência de dados local com Room ou DataStore.
- Consumir e exibir dados de uma API externa.
- Aplicar princípios de design de interface e usabilidade.
- Documentar o projeto e apresentá-lo de forma clara.

O trabalho pode ser feito em equipe
{: .label .label-blue }

## ✅ Requisitos mínimos <a name="req"></a>

-  O aplicativo deverá obrigatoriamente incluir:
  1. Múltiplas telas com navegação entre elas.
  1. Cadastro, edição e exclusão de informações (CRUD).
  1. Persistência local de dados (Room ou DataStore).
  1. Uso de MaterialTheme, com modo claro/escuro.
  1. Integração com API externa.
  1. Utilizar UMA das funcionalidades a seguir: 
        - Uso de GPS/Mapas
        - Uso de sensores.
        - Integração com câmera ou galeria
        - Notificações locais ou push

## ⭐ Funcionalidades Bônus (para pontuação extra)

- Animações, gestos ou outros recursos avançados do Compose.
- Testes unitários ou de interface

### ⚠️ Atenção
  
O código do projeto que vai ser desenvolvido deve ser hospedado no <a href="http://www.github.com" target="_blank">GitHub</a>.
{: .label .label-yellow }

Caso o trabalho seja feito em equipe, cada membro da equipe deve usar seu próprio usuário para escrever código.
{: .label .label-yellow }

Não serão aceitos trabalhos implementados em um único commit.
{: .label .label-red }


## 📊 Critérios de avaliação <a name="criterios"></a>

- Implementação correta e completa dos requisitos funcionais definidos
- Utlização adequada dos conceitos e tecnologias discutidos ao longo do curso
- Boas práticas de desenvolvimento, incluindo organização do código, padrões de nomenclatura, e legibilidade
- Funcionalidade e desempenho da aplicação
- Qualidade da apresentação do trabalho

<!--
| Categoria                            | Requisitos Obrigatórios                                                                                                         | Requisitos Bônus                                                                                    | Pontos |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------ |
| 🟫 **Estrutura do App**              | - Kotlin + Jetpack Compose<br>- MVVM (UI, domínio, dados)<br>- Navegação com Navigation Compose                                 | - Modularização de código (features separadas)                                                      | 15     |
| 🟫 **Persistência de Dados**         | - Persistência local (Room ou DataStore)<br>- Dados salvos entre sessões                                                        | - Sincronização offline/online                                                                      | 15     |
| 🟧 **Consumo de Dados / Integração** | - API externa ou JSON local funcional                                                                                           | - Integração com múltiplas APIs                                                                     | 10     |
| 🟪 **Interação do Usuário**          | - Criar, editar e deletar dados<br>- Lista dinâmica (`LazyColumn`/`LazyRow`)<br>- Feedback visual (Snackbar, mudança de estado) | - Animações, gestos de swipe/drag                                                                   | 20     |
| 🟪 **Layout e Design**               | - MaterialTheme consistente (cores, tipografia)<br>- Tema claro/escuro<br>- Layout responsivo                                   | - Layout adaptativo para tablets<br>- Composables customizados                                      | 10     |
| 🟧 **Funcionalidades Extras**        | - Nenhuma obrigatória além da interação e persistência                                                                          | - GPS / Mapas<br>- Câmera / galeria<br>- Notificações locais ou push<br>- Testes unitários ou de UI | 15     |
| 🟫 **Documentação e Código**         | - Código legível, comentado e organizado<br>- README explicando funcionalidades, tecnologias e arquitetura                      | - Tutorial ou guia rápido de uso do app                                                             | 10     |
| 🟪 **Entrega e Apresentação**        | - App executável em dispositivo ou emulador<br>- Apresentação de funcionalidades em até 10 min                                  | - Demonstração de funcionalidades bônus ou integrações avançadas                                    | 5      |


- 🟫 Estrutura / Persistência / Documentação
- 🟧 Integração / Funcionalidades Extras
- 🟪 Interação / Layout / Apresentação

---

-->

## 📅 Entregas

As entrega serão realizdas via Github e Github classroom.
A seguir você pode conferir o prazo das entragas:

| Entrega | Descrição | Prazo |
|:---|:---|:---|
| Entrega 0 - Proposta | Proposta de aplicativo que a ser desenvolido | {{ page.prazo_proposta }}  |
| Entrega 1 - Primeira versão  das telas | Algumas das telas proposta devem ser entregues utilizando dados fixos (*hardcoded*). Estas versões não precisam ser polidas do ponto de vista UI/UX, são somente as primeiras versões. A quantidade de telas depende do projeto proposto. | {{ page.prazo_telas }} |
| Entrega 2 - Funcionalidade princial | Uma funcionalidade importante do sistema deve ser entregue, mesmo com alguams limitações. Podem usar dados fixos (*hardcoded*) | {{ page.prazo_func }} |
| Entrega 3 - Entrega final | Projeto completo e completamente funcional. [Entregar relato de experiência](https://forms.gle/C2MvRSKnn11odHUq5) | {{ page.prazo_final }} |

{: .important }
> Para ter acesso ao repositório template e o formato da proposta acesso [o assignment no GitHub Classroom](https://classroom.github.com/a/AR7CADm8).

### 🗣️ Apresentação do trabalho <a name="apresentacao"></a>



