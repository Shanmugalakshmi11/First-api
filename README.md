# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Element zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

## POST
## Erstellt eine Item.

# Beispiel:
`POST /itembyid`: Erstellen eine Elemente in der Shopping Liste 

`POST /itembyid/{itemdId}`: Erstellen ein einzelnes Element
**Parameter**: `itemId` - Einzigartige Id des Elements

## LÖSCHEN
## Entfernt eine Item.

# Beispiel:
`DELETE /itembyid`: Entfernt eine Elemente in der Shopping Liste

`DELETE /itembyid/{itemId}`: Entfernt ein einzelnes Elemente 
**Parameter**: `itemId` - Einzigartige Id des Elements



# Beispiel:
# Aktualisiert shopping Liste. 
`PUT /allitems/data`: Aktulisiert alle Elemente in der Shopping Liste

