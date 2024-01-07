<div align="center">

## Paczka 4FUN

<img src="https://github.com/AMXX4u/4FUN/blob/main/assets/main/banner.png"></img>

</div>

<p align="center">
  <a href="#requirements">Wymagania ℹ</a> ×
  <a href="#description">Opis 📄</a> ×
  <a href="#vip">Opis VIP'a 📝</a> ×
  <a href="#configure">Konfiguracja 🛠</a> ×
  <a href="#screenshots">Screenshot 📷</a>
</p>

---

### Description 
- Narzędzia, które ułatwiają prace administracji serwera:
  - **Admin IP** - plugin pozwala wydrukować listę graczy wraz z ich adresami IP,
  - **Admin Listen** - plugin dzięki, któremu admin widzi wszystkie wiadomości na say oraz słyszy wszystkie rozmowy graczy,
  - **Admin Voice** - plugin, który dodaje voice chat dla adminów w celu lepszej komunikacji,
  - **Admin Chat** - plugin został odświeżony, zostały dodane do niego nowe kolory, wiadomości na say również zostały odświeżone.

- Pluginy, które urozmaicają rozgrywke:
  - **ABD** - zaawansowany system pokazywania obrażeń,
  - **Bomb Timer** - licznik do wybuchu bomby, prosty, informacyjny,
  - **Medals** - system medali, medale zdobywane są za zostanie najlepszym graczem mapy,
  - **MVP** - system najlepszego gracza rundy, najlepszy gracz rundy otrzymuje również dodatkowe punkty do rang,
  - **No Team Flash** - jak sama nazwa wskazuje, anty flash dla teamu,
  - **Parachute** - zoptymalizowany spadochron,
  - **Ranks** - rozbudowany system rang,
  - **Reset Score** - gracz otrzymuje możliwość zrestartowania statystyk,
  - **Round Sound** - muzyka na sam koniec rundy, z zapisem opcji włącz/wyłącz,
  - **Server Hud** - informacyjny HUD w lewym górnym rogu,
  - **VIP** - system VIP,
  - **Skins System** - System skinów, który pozwala dodać skiny dla zwykłego gracza, czy też dla VIP'a,
  - **Back Weapons** - Prosty plugin, który pokazuje jaką broń trzymamy aktualnie w "eq",
  - **C4 Model** - Plugin pozwala ustawić customowy model C4,
  - **Custom Flash Light** - Plugin daje nam możliwość odpalenia latarki w różnych kolorach,
  - **2 frags for HS** - Plugin dodaje nam 2 fragi, gdy zabijemy przeciwnika w głowę,
  - **Healing** - System leczenia teammates,
  - **Night sky** - W danych godzinach plugin automatycznie zmieni niebo na jasne/ciemne,
  - **Run Planting** - Plugin pozwala chodzić nam przy plantowaniu bomby,
  - **Money & Bank** - Rozbudowany system monet oraz banku,
  - **Quest** - System misji, podzielony na akty,
  - **Silly C4** - Pozwala nam przykleić bombe np. na skrzynce,
  - **Advertisement** - Plugin będzie wyświetlał co X sekund na czacie reklamy,
  - **Bet** - System betowania za $, gdy nie żyjemy,
  - **Trail Grenade** - Smugi podążające za granatami,
  - **Bonus Knife** - System kos, które dają nam dodatkowe bonusy oraz modele noży,
  - **PTB** - Najsłynniejszy teambalance,
  - **Shop** - System sklepów,
  - **Ruletka** - System ruletki za dolary,
  - **AFK System** - Plugin, który wyrzuca graczy za AFK,
  - **Restore Data** - Plugin przywróci nam nasze statystki, gdy zostaliśmy wyrzuceni z serwera,
  - **Sounds** - KillSounds, dźwięki typu `monsterkill`,
  - **Voice Manager** - Pokazuje kogo nasz team słyszy, dodatkowo zostało wbudowane tam death info (info po śmierci),
  - **Contact** - Kontakt z administracja,
  - **Drop Nades** - Możliwość wyrzucania granatów pod G,
  - **Limit Nade** - Limit kupionych granatów,
  - **Kill info** - Informacja o tym kto nas zabił,
  - **Hostage** - Nieśmiertelne hosty,
  - **Bomb Defuse** - Plugin, który daje nam wybór kabelka, który mamy przeciąć, aby rozbroić bombe,
  - **Warmup** - Rozgrzewka z losowymi brońmi, oraz z losowym only HS,
  - **Mute** - System mutowania & gagowania dla graczy,
  - **BSLimiter** - Limiter graczy na dany BS
  - **Map Manager** - Rozbudowany mapmanager.


### VIP
- VIP posiada:
  - Status VIP w tabeli oraz na czacie
  - Status **VIP** w Tabeli [TAB],
  - Prefix **VIP** na czacie,
  - Kevlar + Defuse za darmo
  - Menu z wyborerm broni dostepne od X rundy
  - Dodatkowe X skok(ow)
  - Dodatkowe $ za fraga X | XX HS
  - Dodatkowe HP za fraga X | XX HS
  - Deagle dostepny od X rundy
  - Granaty dostepne od X rundy
  - Dodatkowe monety za fraga, defuse, plant c4, uratowanie hosta

--- 

> [!TIP]
> Pluginy posiadają własne cvary, więc modyfikacja ich jest bardzo prosta.

### Configure

<details>
  <summary><b>Medale</b></summary>

```cfg
  - amxx4u_medals_host "localhost"
  - amxx4u_medals_user "root"
  - amxx4u_medals_pass "pass"
  - amxx4u_medals_data "database"
  - amxx4u_medals_players "4"
    - Od ilu graczy mają być rozdawane medale?
  - amxx4u_medals_map "10.0"
    - Ile czasu przed zmianą mapy mają być rozdawane medale?
```
</details>

<details>
  <summary><b>Advertisement</b></summary>

```cfg
  - amxx4u_advertisement_time "120"
    - Co ile sekund ma pojawiać się reklama na czacie?
```
</details>

<details>
  <summary><b>BSLimiter</b></summary>

```cfg
  - amxx4u_bsl_min "4"
    - Od ilu graczy pozwalać grać na każdym BS?
```
</details>

<details>
  <summary><b>2 Frags for HS</b></summary>

```cfg
  - amxx4u_hs_kill "1"
    - Ile dodatkowo dawać fragów za zabójstwo HS?
```
</details>


<details>
  <summary><b>Healing</b></summary>

```cfg
  - amxx4u_heal_time "1.25"
    - Co ile sekund można leczyć osobe z Twojego teamu?
  - amxx4u_heal_distance "80.0"
    - Z jakiej odległości można leczyć?
  - amxx4u_heal_health "5"
    - Po ile HP będzie dostawać osoba, która jest leczona?
  - amxx4u_heal_count "5"
    - Ile osób może leczyć dana osobe?
```
</details>

<details>
  <summary><b>Run planting</b></summary>

```cfg
  - amxx4u_planting_speed "100.0"
    - Jaką prędkość może osiągnąć gracz plantujący C4?
```
</details>

<details>
  <summary><b>Monety & Bank</b></summary>

```cfg
  - amxx4u_money__host "localhost"
  - amxx4u_money_user "root"
  - amxx4u_money_pass "pass"
  - amxx4u_money_data "database"

  - amxx4u_bank_transfer_limit "5000"
    - Dzienny limit przesyłania monet
  - amxx4u_money_kill "1"
    - Ile monet otrzymuje gracz za zabójstwo?
  - amxx4u_money_kill_hs "2"
    - Ile monet otrzymuje gracz za zabójstwo HS?
  - amxx4u_money_planted "1"
    - Ile monet otrzymuje gracz za podłożenie C4?
  - amxx4u_money_defused "1"
    - Ile monet otrzymuje gracz za rozbrojenie C4?
  - amxx4u_money_hostage_rescue "1"
    - Ile monet otrzymuje gracz za uratowanie hosta?
  - amxx4u_money_round_winner "1"
    - Ile monet otrzymuje gracz za wygranie rundy?
```
</details>


<details>
  <summary><b>MVP</b></summary>

```cfg
  - mvp_kill_points "1"
    - Ile punktów za zabójstwo gracza
  - mvp_killhs_points "2"
    - Ile punktów za zabójstwo gracza w glowe
  - mvp_planted_points "2"
    - Ile punktów za podłożenie bomby
  - mvp_explode_points "3"
    - Ile punktów za wybuch bomby dla plantującego
  - mvp_defused_points "2"
    - Ile punktów za rozbrojenie bomby
  - mvp_ctwin_points "1"
    - Ile punktów za wygranie rundy przez CT
  - mvp_ttwin_points "1"
    - Ile punktów za wygranie rundy przez TT
  - mvp_reward_points "1"
    - Ile punktów doliczyć do rangi za zostanie MVP
```
</details>

<details>
  <summary><b>Parachute</b></summary>

```cfg
  - amxx4u_parachute_enable "1"
    - Czy spadochron ma być włączony?
  - amxx4u_parachute_team "0"
    - Dla jakiej drużyny ma być spadochron? (0 = WSZYSCY)
  - amxx4u_parachute_speed "-150.0"
    - Jaka ma być prędkość spadania?
```
</details>

<details>
  <summary><b>Ranks</b></summary>

```cfg
  - amxx4u_rank_host "localhost"
  - amxx4u_rank_user "root"
  - amxx4u_rank_pass "pass"
  - amxx4u_rank_data "database"
  - amxx4u_rank_players "4"
    - Od ilu graczy ma dodawać punkty do rangi?
  - amxx4u_rank_pkt_kill "1"
    - Ile punktów ma otrzymywać gracz za zabójstwo?
  - amxx4u_rank_pkt_hs "1"
    - Ile punktów ma otrzymywać gracz za zabójstwo w głowe?
  - amxx4u_rank_pkt_plant "1"
    - Ile punktów ma otrzymać gracz za zaplantowanie C4?
  - amxx4u_rank_pkt_defuse "1"
    - Ile punktów ma otrzymać gracz, który rozbroił C4?
  - amxx4u_rank_pkt_round "1"
    - Ile punktów ma otrzymać drużyna, która wygrała runde?
```
</details>

<details>
  <summary><b>VIP</b></summary>

```cfg
  - vip_player_flag "t"
    - Jaką flagę musi posiadać gracz, aby otrzymać VIP'a?
  - vip_gunmenu_round "3"
    - Od której rundy ma byc wyświetlane menu broni?
  - vip_kill_money "100"
    - Ile dolarów VIP otrzymuje za zabicie gracza?
  - vip_hs_money "200"
    - Ile dolarów VIP otrzymuje za zabicie gracza w głowe?
  - vip_kill_hp "5"
    - Ile HP VIP otrzymuje za zabicie gracza?
  - vip_hs_hp "10"
    - Ile HP VIP otrzymuje za zabicie gracza w głowe?
  - vip_grenade_round "2"
    - Od której rundy VIP ma dostawać granaty?
  - vip_deagle_round "2"
    - Od której rundy VIP ma dostawać deagle?
  - vip_jump_enable "1"
    - Dodatkowe skoki dla VIP'a mają być właczone?
  - vip_jump_num "1"
    - Ile dodatkowych skokow dla VIP'a?
  - vip_money "2"
    - Ile VIP ma otrzymać monet za zabójstwo?
  - vip_money_hs "4"
    - Ile VIP ma otrzymać monet za zabójstwo HS?
  - vip_money_planted "2"
    - Ile VIP ma otrzymać monet za podłożenie bomby?
  - vip_money_defused "2"
    - Ile VIP ma otrzymać monet za rozbrojenie bomby?
  - vip_money_hostage "1"
    - Ile VIP ma otrzymać monet za uratowanie hosta?
```
</details>

### Screenshots

<details>
  <summary><b>Admin Chat</b></summary>
  
- Nowe kolory

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/admin/admin_lime_say.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/admin/admin_pink_say.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/admin/admin_violet_say.png"></img>

- Odświeżone informacje na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/admin/admin_chat_mplayer.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/admin/admin_chat_madmin.png"></img>

</details>

<details>
  <summary><b>Admin IP</b></summary>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/admin/ip.png"></img>

</details>

<details>
  <summary><b>VIP</b></summary>
  
- Opis VIP'a w MOTD.

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/vip/motd.png"></img>

- Menu wyboru broni.

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/vip/weapon.png"></img>

- Informacja po wyborze broni

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/vip/chat.png"></img>
</details>

<details>
  <summary><b>Money & Bank System</b></summary>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/money/register.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/money/main_menu.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/money/pay.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/money/withdraw.png"></img>
  
- Inforamcja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/money/chat_1.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/money/chat_2.png"></img>
</details>

<details>
  <summary><b>HUD</b></summary>
  
- Główny HUD

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/other/hud.png"></img>
</details>

<details>
  <summary><b>System Misji</b></summary>
  
- Menu główne

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/questy/main.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/act_x.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/questy_select.png"></img>
  
- Informacje na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat_0.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat_2.png"></img>
</details>

<details>
  <summary><b>System Betowania</b></summary>
  
- Menu główne

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/menu_1.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/menu_2.png"></img>
  
- Informacje na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat_2.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat_3.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat_4.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/bet/chat_5.png"></img>
</details>

<details>
  <summary><b>Kontakt z administracja</b></summary>
  
- MOTD

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/contact/contact.png"></img>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/contact/menu.png"></img>

- Konsola

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/contact/console.png"></img>

- Inforamcja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/contact/chat.png"></img>
</details>

<details>
  <summary><b>Skins System</b></summary>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/skins/main_menu.png"></img>
  
- Inforamcja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/killsound/set_skin.png"></img>
</details>

<details>
  <summary><b>Sklep</b></summary>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/sklep/shop_main.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/sklep/shop_doll_1.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/sklep/shop_doll_2.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/sklep/shop_money.png"></img>
  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/sklep/shop_prefix.png"></img>

- Inforamcja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/sklep/set_prefix.png"></img>
</details>

<details>
  <summary><b>Kill Sounds</b></summary>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/killsound/menu.png"></img>
  
- Inforamcja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/killsound/chat.png"></img>
</details>

<details>
  <summary><b>Custom Flash Light</b></summary>

  <video src='https://github.com/AMXX4u/4FUN/assets/50671740/7dc8d5d8-ee41-45c8-866d-c38896c0ca1d'>
  
</details>

<details>
  <summary><b>Kill Info</b></summary>
  
- Informacja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/othe/kill_info.png"></img>

</details>

<details>
  <summary><b>Knife bonus</b></summary>
  
- Menu

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/knife/main.png"></img>
  
- Inforamcja na czacie

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/knife/chat.png"></img>
</details>

<details>
  <summary><b>RoundSound</b></summary>
  
- Główne menu roundsound

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/res/main.png"></img>
  
- Lista utworów

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/res/music.png"></img>
</details>

<details>
  <summary><b>TOP'ki</b></summary>
  
- TOP Medale

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/other/medal.png"></img>
  
- TOP Rangi

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/other/ranks.png"></img>

- TOP 10

  <img src="https://github.com/AMXX4u/4FUN/blob/main/assets/other/top10-.png"></img>
</details>

### Requirements 
> [!NOTE]  
> Poniżej przedstawiamy Wam liste modułów wymaganych wraz z wersjami. Na tych wersjach pluginy były pisane, przerabiane.

- AMXModX 1.10.0.5467
- ReHLDS 3.13.0.788
- ReAPI 5.24.0.300
- ReGameDLL 5.26.0.668
