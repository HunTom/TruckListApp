# TruckListApp
MVC tanulófeladat

#Lista létrehozása
- A HomeControllerben létrehozunk egy új controllert ami majd vezérli az új Truck view-t
- A listát model-el akarjuk kezelni ezért létrehozunk egy új class-t a model alatt
- Amikor a listát meggeneráljuk, akkor a lista típusaként a model nevét adjuk és a Visul Studióval felvetetjük a using részbe

## Elemek hozzáadása a listához
Lista neve.Add(new modelnév() {oszlopnév = "adat", oszlopnév = "adat", oszlopnév = "adat", })


### Lista megjelenítése
- Az újonnan létrehozott view-ban hozzáadjuk a modelt és annak típusát @model List<AppName.Models.ModelName>
- Létrehozunk egy HTML listát pl <ol> és ebben egy foreach ciklust @foreach(var elem in Model) {<li>@elem.oszlopneve</li>}
- A C# kódoknál fontos, hogy előtte legyen a @
