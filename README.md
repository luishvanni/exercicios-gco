commits usam a regra do https://www.conventionalcommits.org/en/v1.0.0/ 

**main** &rarr; branch principal
**dev** &rarr; branch de desenvolvimento
**pre-prod** &rarr; branch de homologação

Branches de funcionaldiades
* feat/func-a
* feat/func-b
* feat/func-c
* feat/func-d

Branches de bugs
* bug/erro-a1
* bug/erro-a2
* bug/erro-a3


## Estratégia de Branches — Trunk-Based Development

Adotamos a estratégia **Trunk-Based Development**, onde:

- A branch principal `main` concentra o desenvolvimento.
- Branches de funcionalidade (`feat/...`) ou correções rápidas (`hotfix/...`) são criadas a partir da `main`.
- Essas branches são curtas: após concluídas, são mergeadas de volta na `main` e depois removidas.
- As antigas branches `dev` e `pre-prod` não são mais utilizadas.
