Egy autókereskedést tervezek modellezni a szoftverrel, parancssorral kezelhető.

Még nem tudom pontosan milyen mintákat fogok használni, de példák:
Singleton: az ügyvezetőnek bárki tehet fel bizonyos kérdéseket (metódusok hívása), de ügyvezetőből csak egy van, őt a getInstance-al érjük el
Prototype: pl ha azt mondja az ügyvezető, hogy “külföldről hozzunk be 100 ugyanilyen autót mint amit az előbb jó áron eladtunk”, akkor abból az autóból kell legyártani 100 példányt
Adapter: az autók hazaszállítására elküldjük a sorfőt vonattal, aminek odaadjuk az autót, és őt utasíthatjuk pozícióváltásra (hozza haza az autót amiben ül), ezzel együtt az autó koordinátája is változik. (Tehát az autónak van koordinátája, de nem módosítható önmagában. Egy sofőrt kell adapternek használni ahhoz, hogy az autót mozgassuk)
Observer: az ügyfél várja, hogy végre megérkezzen az autója. A kereskedő küld neki egy SMS-t, amikor a sofőr (adapter) a külföldről rendelt autóját leszállította a kereskedésbe.
