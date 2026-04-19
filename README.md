# Ročníková práce
Software: Unity
Jazyk: C#
Téma: Tower defense-ish roguelike s velkou inspirací z Teamfight Tactics https://teamfighttactics.leagueoflegends.com/cs-cz/

## Princip
### Shrnutí
Hráč získává troopky, které může spojovat aby je vylepšil

Troopky defendují základnu od nepřátel, kteří posílají útoky

Součástí útoků budou i *weak pointy*, které když hráč damaguje, damaguje i enemáka, který ten attack poslal

Zničení weak pointu odmění hráče s trochou coinů, bariérou, a extra damage na enemáka 

Mezi encountry hráč může nakupovat troopky

### Třídy 
Každá troopka má minimálně 1 třídu

Každá třída dává hráčovi teamu vlastní schopnosti

Síla schopností třídy se odvíjí od počtu troopek které máte na hracím poli s atributem té třídy

U každé třídy je tento počet jinačí, ale většina tříd své schopnosti začne dávat od 2 troopek

### Troopky
Max *10?* troopek v hracím poli, hráč ze začátku bude mít 3 sloty - 2 DPS sloty a 1 support slot

Další sloty si může hráč získat z různých odměn, ale hlavně z shopu

DPS - Troopky které střílí ve směru kurzoru, hlavní zdroj damage, různé druhy - shotgun, pistol, laser, ...

Support - Nestřílí, ale jinak podporují team - generace bariéry, zvyšování damage DPS troopek, vydělávání peněz, vytváření itemů, ...

Special - Různé efetky, jen pár special troopek ve hře 

### Bariéra
Bariéra chrání základnu od poškození - 1 bariéra = 1 damage blocknutý

Zdroje - enemy weak pointy, troopky, itemy, augmenty

Hráč může mít max. *1000?* bariéry, bariéra se resetu na začátku každého encounteru

## Progress
Před 17. 4. - Vymýšlení principu, pár spritů, kód pro střílení z turrety, spawnovaní enemy attacků, interakce s němi

17. 4. - Slime sprite, vytváření systému pro generaci dungeonu
