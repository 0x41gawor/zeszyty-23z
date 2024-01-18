# SOA

## Web Service

![image-20240117175748653](img/image-20240117175748653.png)

Ratkowski nie wiem co tu rozumie jako web service. 

Architektura Usługowa - Service Oriented Architecture

**Usługa** - wejście -> zachowanie -> wyjście
Cechy usługi:

- autonomia
- komponowalność
- reużywalność
- bezstanowość - użycie usługi nie modyfikuje stanu tej usługi
- abstrakcja od implementacji
- “luźne powiązanie” (loosely coupling)
- “odkrywalność” (discoverability) - możliwość odszukania pożądanej usługi
- interoperacyjność - niezależność od platformy

**Web Service** - To inaczej usługa internetowa, która pozwala na komunikowanie się klientowi z serwerem za pomocą sieci. Standardy to REST albo SOAP. Oba te standardy wpisują się w standard usługi zdefiniowanej poprzez SOA. Tak, więc Web Service też.

## SOA nieprawdziwe

![image-20240118143313631](img/image-20240118143313631.png)

No to takie na logikę xd

## Orkiestracja to

![image-20240117180838974](img/image-20240117180838974.png)

**Orkiestracja** - opis, w jaki sposób usługi składowe działają, żeby stworzyć nową usługę

![image-20240117180746287](img/image-20240117180746287.png)

## Usługa bezstanowa

![image-20240117193318599](img/image-20240117193318599.png)

## Cechy SOA

![image-20240117194103682](img/image-20240117194103682.png)

**Usługa** - wejście -> zachowanie -> wyjście
Cechy usługi:

- autonomia
- komponowalność
- reużywalność
- bezstanowość - użycie usługi nie modyfikuje stanu tej usługi
- abstrakcja od implementacji
- “luźne powiązanie” (loosely coupling)
- “odkrywalność” (discoverability) - możliwość odszukania pożądanej usługi
- interoperacyjność - niezależność od platformy

## BPEL

![image-20240118144613027](img/image-20240118144613027.png)

**Business Process Execution Language for Web Services** (BPEL or BPEL4WS) is a language used for the definition and execution of business processes using Web services.

# Architektura Korporacyjna

## TOGAF to

![image-20240118141511661](img/image-20240118141511661.png)

To najwyższego poziomu wzorzec na to jak w ogóle podejść do tematu Enterprise Architecture. 

## Togaf ADM a Archimate

![image-20240117192810451](img/image-20240117192810451.png)

TOGAF ADM to metodologia na tworzenie Architektury Korporacyjnej. Zawiera opis jak zrobić desing, planowanie, implementacje i zarządzanie architekturą korporacyjną. 

Archimate to diagramowy język modelowania, który służy do reprezentowania Architektury Korporacyjnej.

TOGAF ADM jako jeden z elementów ma język modelowania i może nim być, a wręcz zalecany jest Archimate. 

## Archimate: elementy behavioralne

![image-20240117193441436](img/image-20240117193441436.png)

Są 3:

- Stukturalne - określają rzeczy, które mogą robić aktywności
- Behavioralne - określają aktywności
- Informacyjne - reprezentują dane

<img src="img/image-20240117193610124.png" alt="image-20240117193610124" style="zoom:50%;" />

## Core concepts Archimate są podzielone na warstwy

![image-20240117194230865](img/image-20240117194230865.png)

![image-20240117194259913](img/image-20240117194259913.png)

## faza Architecture Vision w TOGAF ADM

![image-20240117194353237](img/image-20240117194353237.png)

![image-20240117194423851](img/image-20240117194423851.png)

![image-20240117194431869](img/image-20240117194431869.png)

![image-20240117194442161](img/image-20240117194442161.png)

## Algebraiczna definicja EA

![image-20240118141843589](img/image-20240118141843589.png)

**EA: {R, B, A, D, S, T, C, M}**

- R(**Requirements**) zbiór wymagań systemowych
- B (**Business Processes**) zbiór procesów biznesowych
- A (**Applications**) zbiór aplikacji biznesowych
- D (**Data**) zbiór danych
- S (**Systems**) zbiór systemów oprogramowania
- T (**Technical components**) zbiór komponentów technicznych
- C (**Constraints**) zbiór ograniczeń dotyczących poszczególnych elementów zbioru EA
- M (**Metrics**) zbiór miar, które charakteryzują architekturę korporacyjną

## EA żeni biznes z systemami IT do jego usprawniania

![image-20240118145059223](img/image-20240118145059223.png)

## Fałszywe zdanie

![image-20240118145237840](img/image-20240118145237840.png)



# DDD

## Domeny

![image-20240117193714704](img/image-20240117193714704.png)

Modelowanie odbywa się w 4 zasadniczych domenach:

- Biznesowa
  - Modelujemy procesy biznesowe, procesy które przynoszą kasę
- Danych
  - Modelujemy dane, relacje między nimi, oceniamy potrzebność ich trzymania, robimy Big Data
- Aplikacji
  - Modelujemy apki w naszych systemach
- Techniczna
  - Modelujemy infra naszych sieci



