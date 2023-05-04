---
name: Order IT material
description: Managing the order process for goods and services.
title: 'Order: [Product name] for [purpose or end user]'
---
<!-- 1. Describe order -->
## Order description
### End user / purpose

### Items
| Name | Cost <!-- Specify currency if not in CAD --> |
| :--- | ---: |
| Item 1  | 00.00 |
| Item 2  | 00.00 | <!-- Add items by copy-pasting -->
| **Total** | **00.00 $** |

### Funds to use
<!-- Project funding to use for the purchase-->

### Delivery

#### Poste Canada

If shipping is done through Poste Canada, use the following address:
```yml
Université de Montréal
Pavillon de la Faculté de l'aménagement, École d'architecture de paysage
CP 6128 Succursale Centre-ville
Montréal (Québec) H3C 3J7
```
Once received by the school, the package will be transfered to the faculty building and then delivered directly to the indicated room.

#### Any other

Else, if shipping is done through another company (UPS, FedEx, etc.), use:
```yml
Pavillon Roger-Gaudry / Campus Réception – Quai #1
École d’architecture de paysage – Local [0000]
2900 boulevard Edouard-Montpetit
Montréal, QC, H3T 1J4
```

### References

If you are uncertain of the process prescribed by the school for the purchase planned here, refer to the university's [**documentation on making a purchase request**](https://approvisionnement.umontreal.ca/faire-une-demande-dachat/faire-une-demande-dachat/#moins-de-25-000). Although it can often simplify the task, it is not always necessary to limit the product choices to a pre-approved provider (such as INSO).

#### Providers

| Provider | Catalog | Contact |
| --- | --- | --- |
| INSO | https://shop.inso.ca/catalogue | infoudem@inso.ca |

## Order actions:

- [ ] — Action: Choose material from provider’s catalog
- [ ] — Action: Email provider, with detailed items' list and specifying funding source (prices are adjusted in certain cases)
- [ ] — Action: Create ordre project folder in [orders directory](https://github.com/CUPUM/general/tree/main/equipment/orders) as ```yyyymmdd-[order_project_name]``` (ex. 20221124-mac_book_air_koseki)
- [ ] – Action: Place all documents in newly created ordre project folder
- [ ] — Action: Forward submission document to the C. Benoit (chantal.benoit@umontreal.ca) with Shin in cc.
- [ ] Wait for order (add ```waiting``` tag)
- [ ] — Action: Email C. Benoit to confirming reception of order
- [ ] — Action: Append new items to [equipment log](https://github.com/CUPUM/general/blob/main/equipment/beaudrymarchand-log-equipment-20221013.csv)
- [ ] — Action: Place all additional documents (receipts, warranty, etc.) in created order project folder
