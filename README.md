# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Element zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

 `PUT /newitem`: Fügt neues Element der Liste hinzu.

 `DELETE /delitem`: Entferne Element(e) aus der Liste.

 `PUT /itembyid/{itemId}`: Aktualisieren eines Elements.
**Parameter**: `itemId` - Einzigartige Id des Elements