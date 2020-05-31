# Database Format

Die Datenbank stellt in erster Linie eine einfach JSON Datei dar.

Der Preis soll UVP angegeben werden in Dollar in Float.

```json
{
    "version": 0.1,
    "author": "My name",
    "license": "ISC",
    "keys": [
        {
            "name": "Key 1",
            "source": "https://source.com/",
            "imgUrl": "https://imgurl.com/",
            "tags": ["Tag 1", "Tag 2", "Tag 3"],
            "price": 49.99,
            "shop": [
              {
                "name": "Shop 1",
                "website": "https://shop1.com/"
              },
              {
                "name": "Shop 2",
                "website": "https://shop2.com/"
              }
            ],
            "features": ["Feature 1", "Feature 2", "Feature 3"],
            "socketA": true,
            "socketC": true,
            "nfc": true,
            "u2f": true,
            "fido2": true,
            "openSource": true,
            "protocols": ["CTAP1", "CTAP2"]
        }
    ]
}

```
