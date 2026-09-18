# Parbalans

Ett litet sidoprojekt för att öva fullstack-utveckling genom att bygga en app för månadsbalansering hos par med delad ekonomi – dvs räkna ut vem som är skyldig vem hur mycket i slutet av månaden, baserat på vad var och en har lagt ut. Följande funktioner:

- Låta paret registrera transaktioner
- Räkna ut saldot mellan de två i slutet av månaden
- Visa vem som ska betala vem och hur mycket för att jämna ut

**SQL**
psql -h localhost -U minanvandare -d parbalans

**Spring Boot**
./mvnw spring-boot:run
