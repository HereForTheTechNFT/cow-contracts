# CoW Protocol : architecture

Le cœur du système s’articule autour des ordres, des solutions de solver et du contrat de settlement. Le settlement vérifie les signatures, les balances, les allowances et les règles d’exécution avant de transférer les tokens.

Les enchères par lots permettent de partager une liquidité et de rechercher des coincidences entre demandes. Les contrats d’authentification et de vault relayer bornent les appels autorisés et les flux de règlement.

La frontière on-chain/off-chain est essentielle : le contrat arbitre la validité, les services construisent la solution.

[Chapitre suivant : ordres et settlement](03-ordres-settlement.md)
