---
id: products
title: Products endpoint
sidebar_label: /products
---

## JSON example

``` json
{
    "title": "adidas Ace 16.1 SG, Botas de fútbol Hombre", // required
    "id": "B01FWRYM68", // required
    "description": ".", // required
    "images": [ // required
        "https://dev.alchersan.com/images/2.645-202.0/image1",
        "https://dev.alchersan.com/images/2.645-202.0/image2"
    ],
    "available": true, // required
    "price": 199.95, // required
    "ship_price": 6.00,
    "discount": null,
    "date": null,
    "category": ["Shoes", "Clothes"], // required
    "subcategory": ["Sport", "Football"],
    "brand": "Adidas",
    "gender": "male/female/unisex",
    "label": "OFERTA!",
    "score": 0,
    "stock": [
            {
                "color": "yellow",
                "sizes": [
                    "39 EU",
                    "40 2/3 EU",
                    "42 EU"
                ]
            },
            {
                "color": "green",
                "sizes": [
                    "43 EU",
                    "44 2/3 EU",
                    "46 EU"
                ]
            }
        ],
    "metadata": {
        "features": [
            {
                "title": "Material exterior",
                "description": "Sintético"
            },
            {
                "title": "Revestimiento",
                "description": "Tela"
            }
        ],
        "specs": [
            {
                "spec": "Diámetro",
                "measure": "",
                "value": "1/2\", 5/8\", 3/4\""
            },
            {
                "spec": "Dimensiones (la. × an. × al.).",
                "measure": "(mm)",
                "value": "65 x 33 x 45"
            },
            {
                "spec": "Peso",
                "measure": "kg.",
                "value": "68,5"
            }
        ]
    },
    "rating": [5, 4, 1, 5, 4, 4, 2, 3],
    "comments": [
        {
            "name": "Andrea",
            "rating": 5,
            "title": "Calzano alla perfezione",
            "date": "05/02/2018",
            "description": "Scarpe di ottima fattura e curate finiture. Ottima calzata e resistenza all'usura. Molto apprezzato il set di tacchetti aggiuntivi all'interno. Consiglio.",
            "response": null
        },
        {
            "name": "Sandra R.",
            "rating": 4,
            "title": "Oben zu weit",
            "date": "25/06/2016",
            "description": "Optisch ansprechend, leider am Schaft wesentlich weiter geschnitten als erwartet, daher passt der FB -Schuh leider nicht und musste zurückgehen.",
            "response": "Gracias por tu comentario, eres el amo."
        }
    ]
}
```
