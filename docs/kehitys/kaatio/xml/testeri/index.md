---
layout: "swagger-ui"
description: ""
id: "testeri"
openapi-url: "http://kaati-appli-f2m5ln8ufioi-920207514.eu-west-1.elb.amazonaws.com/openapi.json"
---
# Kaava-XML:n simuloitu tallennuspalvelu

Tässä kuvattu rajapinta simuloi KAATIO-projektissa määritellyn XML-muotoisen kaavatiedon tallennusrajapintaa. Rajapinta on laadittu KAATIO-hankkeen aikaista ohjelmistojen testausta varten, eikä se ole tarkoitettu operatiiviseen käyttöön.

Rajapinta ottaa vastaan XML-muotoisen kaavan paketoituna ```LandUseFeatureCollection```-juurielementin sisään, kuten kuvattu [Esimerkit-sivulla](../esimerkit/). Lähetettäviä tiedostoja ei tallenneta mihinkään.