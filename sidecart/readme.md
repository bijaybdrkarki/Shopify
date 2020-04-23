
<---IF you need any help create an issue here---->
<br />
Since this cart should be availble in every page.
1. create new snippet file (eg: sidecart.liquid) and add code of sidecart.liquid into it.
2. open settings_schema.json (inside of config folder), scroll all the way to bottom (just before closing big bracket) add this (if you want more than 3 products for suggestion copy code of settings and add more)
   ```json
    ,
    {
        "name": {
        "en": "Sidecart"
        },
        "settings": [
            {
                "type": "text",
                "default": "Sidecart",
                "id": "sidecart_title_2",
                "label": "Sidecart Title"
            },
            {
                "type": "product",
                "id": "sidecart_empty_cart_1",
                "label": "sidecart Product 1"
            },
            {
                "type": "product",
                "id": "sidecart_empty_cart_2",
                "label": "sidecart Product 2"
            },
            {
                "type": "product",
                "id": "sidecart_empty_cart_3",
                "label": "sidecart Product 3"
            }
        ]
    }
   ``` 

