**Sammanfattning**  
Gruppen testade Acme Corp Internportal i en avgränsad testmiljö. Gruppen hittade sex säkerhetsproblem: tre kritiska och tre allvarliga.

Problemen handlade bland annat om inloggning, behörigheter, användarinformation och åtkomst till intern data. Testet visade att flera problem kunde påverka varandra och ge större risk.

Rapporten säger inte att problemen har lagats eller testats igen. Därför behöver organisationen planera åtgärder och kontrollera dem med ett nytt test.

**Tre lärdomar**  
**1\. Flera problem kan påverka varandra**  
Flera problem kunde användas tillsammans. När problem kombineras kan följderna bli allvarligare än när man tittar på ett problem i taget.

**Lärdom:** Vi behöver se hur problemen hänger ihop. Vi behöver också tänka på vad som kan hända om någon använder flera problem tillsammans.

**2\. Servern måste kontrollera behörigheter**  
En användare ska inte själv kunna bestämma vilka rättigheter hen har. Systemet måste kontrollera vem användaren är och vad användaren får göra.

**Lärdom:** Servern ska kontrollera behörigheter. Information som användaren skriver in måste hanteras säkert. Det minskar risken för att någon får åtkomst till funktioner eller data utan tillåtelse.

**3\. Tydliga anteckningar är viktiga**  
Rapporten beskriver olika resultat från två testtillfällen. Orsaken till skillnaden är inte känd. Det gör det svårare att jämföra resultaten.

**Lärdom:** Skriv tydligt när och var testet gjordes, vad gruppen såg och vad som inte kunde kontrolleras. Då kan andra förstå hur slutsatserna togs fram.

**Rekommendationer**

* Ge varje problem en ansvarig person och ett slutdatum.  
* Börja med de kritiska problemen.  
* Begränsa åtkomsten till intern data.  
* Kontrollera att systemet bara ger användare den åtkomst de behöver.  
* Gör ett nytt test efter att problemen har lagats.  
* Skriv ner vad som testades och vad resultatet blev.  
* Säg inte att ett problem är löst förrän lösningen har testats.

**Användning av AI**  
Projektunderlaget säger att AI användes för att hjälpa till med analys, ordning och text. AI kan hjälpa till att sortera information och göra en rapport lättare att läsa.

Men AI kan ge fel svar eller missa viktiga detaljer. Därför måste tekniska resultat kontrolleras mot bevisen från testet. AI ersätter inte riktiga tester eller människors beslut. Känslig information ska inte delas med ett AI-verktyg om det inte är godkänt.  
