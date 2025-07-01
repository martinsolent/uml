---
layout: default
title: Prompts
nav_order: 3
---

{: .no_toc }

# Mermaid & VS Code 

On an AI platform ask to generate:

```
Create mermaid code for a flow chart for making a cup of tea
```

![](../img/mermaid_imgs_2025/mermaid_2025_1.png)

Toggle to show code and then copy 

![](../img/mermaid_imgs_2025/mermaid_2025_2.png)

Here is the Copied Code:

```
 flowchart TD
    A[Start] --> B[Boil Water]
    B --> C{Do you want milk?}
    C -- Yes --> D[Add milk to cup]
    C -- No --> E[Place tea bag in cup]
    D --> E
    E --> F[Pour hot water into cup]
    F --> G[Steep tea for a few minutes]
    G --> H{Add sugar or honey?}
    H -- Yes --> I[Add sweetener]
    H -- No --> J[Skip sweetener]
    I --> K[Stir and enjoy]
    J --> K
    K --> L[Done] 

```


In VS Code intall Mermaid Chart exstension

![](../img/mermaid_imgs_2025/mermaid_2025_4.png)

Cut and paste into VS Code

Create diagrams in markdown using mermaid fenced code blocks:

```
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
```
You can also use ::: blocks:

::: mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
:::


![](../img/mermaid_imgs_2025/mermaid_2025_3.png)



