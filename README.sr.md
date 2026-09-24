<a href="https://svilenkovic.com/en/aplikacija-admin-panel"><img src="media/cover.jpg" alt="Admin Panel, naslovna strana na laptopu i telefonu" width="100%"></a>

# Admin Panel

Moj interni panel za sajtove koje hostujem: klijenti, naplata sa kursevima valuta, podsetnici, statistika, CLI i cron poslovi preko SSH-a.

[Stranica aplikacije](https://svilenkovic.rs/aplikacija-admin-panel) · [English](README.md)

> [!NOTE]
> Moj sopstveni proizvod. Izvorni kod je privatan. Ova stranica opisuje šta radi i kako je napravljen.

<table>
  <tr><td><b>Klijent</b></td><td>Sopstveni proizvod</td></tr>
  <tr><td><b>Delatnost</b></td><td>Hosting i upravljanje sajtovima</td></tr>
  <tr><td><b>Lokacija</b></td><td>Srbija</td></tr>
  <tr><td><b>Vrsta</b></td><td>Interna web aplikacija</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, MariaDB, SSH, cron, systemd</td></tr>
</table>

## O projektu

Ovo je panel iz kog vodim hosting. Sajtove, klijente kojima pripadaju, naplatu sa kursevima valuta, podsetnike i statistiku drži u jednoj aplikaciji. Uz svaki domen pokazuje stanje sertifikata, a nadzor prati dostupnost, disk i procesor.

Rad na serverima ide preko SSH-a, pa panel tako pokreće i CLI komande i cron poslove. Svaka izmena ulazi u audit log koji beleži ko je šta promenio i kada. Zapisi su heširani, pa se log ne može naknadno tiho očistiti.

## Šta sam uradio

- Sajtovi i klijenti kojima pripadaju, sa stanjem sertifikata za svaki domen
- Naplata i kursevi valuta u istoj aplikaciji sa sajtovima i klijentima
- Podsetnici i statistika nad istim podacima
- CLI komande i cron poslovi koji se izvršavaju preko SSH-a
- Nadzor dostupnosti, diska i procesora, sa upozorenjem kada nešto pređe granicu
- Audit log o tome ko je šta menjao i kada, heširan tako da se zapisi ne mogu tiho ukloniti

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Admin Panel, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Admin Panel, naslovna strana na telefonu"></td>
  </tr>
</table>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
