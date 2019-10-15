## Canibais e Missionários

Resolvendo o problema dos 3 canibais e 3 missionários tentando atravessar um rio com o algoritmo de Busca em Largura (BFS), implementado em python. 

As regras são de que:
1. O barco pode levar no máximo 2 pessoas
2. Sempre devem ter mais missionários do que canibais em uma dada margem do rio.

Os estados serão representados com [#M, #C, #B]. Onde M representa os missionários, C os canibais e B se o barco está, ou não, na margem do rio podendo B, assim, ser 1 (está na margem) ou 0 (está do outro lado).

Ou seja: 

**Estado Inicial**: [3,3,1] -> Todos os missionários e canibais de um lado + o barco

**Estado Final**: [0,0,0] -> Todos passaram



