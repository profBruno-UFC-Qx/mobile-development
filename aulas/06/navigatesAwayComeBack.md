---
title: Usuário sai da aplicação e volta
parent: Cenários com mudanças no ciclo de vida
layout: default
---

## {{ page.title }}

```mermaid
sequenceDiagram
    participant User
    participant Activity
    participant ViewModel
    participant OS

    Note over Activity, ViewModel: App is running and visible.
    
    Note over User, OS: User presses the Home button.
    User->>OS: Press Home
    OS->>Activity: onPause()
    OS->>Activity: onStop()
    Note over Activity: Activity is no longer visible.
    Note over ViewModel: ViewModel is unaffected.

    Note over User, OS: User returns to the app later.
    User->>OS: Selects app from Recents
    OS->>Activity: onRestart()
    OS->>Activity: onStart()
    OS->>Activity: onResume()
    Note over Activity: Activity is visible and interactive again.
 ```
