# IDOS_Compact
CSS pro nový IDOS

Zmenší prostor, který zabírají výsledky hledání spojení novou verzí aplikace IDOS.cz (https://idos.idnes.cz/) resp. CP.sk
(https://cp.hnonline.sk).

Styl se snaží upravit výsledky hledání spojení tak, aby zabíraly, pokud možno, co nejméně místa. Úprava může mít vliv i na další
výsledky hledání (Odjezdy, Zastávkové jízdní řády), ale nebyla pro ně primárně zamýšlena a za případné chyby v těchto výstupech
neručím.

Záměrně jsem ve stylu (v těch případech, kdy to bylo možné) neodstraňoval zobrazení reklam, přestože by to u některých šlo
provést. Nechci poškozovat společnost, pro kterou pracuji.

Styl se budu snažit průběžně ladit v těch případech, kdy objevím nějakou vyloženou chybu v zobrazování.

Update 9.10.2019
Doplnil jsem styly pro tisk, kde jsem provedl zvětšení velikosti písma pro tiskové výstupy výsledků hledání. V případě tisku ZJŘ
jsem navíc doplnil oddělující čáru mezi jednotlivými řádky tabulky, pro lepší čtení.

Update 25.11.2019
Rozhodl jsem se styl přejmenovat na IDOS Compact

Update 9.1.2020
Doplnil jsem jedno pravidlo pro zhuštění řádku s linkou (název dopravce jej zbytečně roztahoval, tak jsem nastavil povinně jen
jeden řádek, zbytek případně přeteče).

Update 29.1.2020
Doplnil jsem jedno pravidlo pro nezalamování názvů měst při volbě města ve funkci ZJŘ.

Update 31.1.2020
Pokus o doplnění tmavého tématu aplikace. Nebyly určitě postiženy všechny prvky a u některých to ani nešlo (styly jsou
definovány přímo v HTML použitím style=). Mělo by se projevovat pouze v případě, že je zvoleno tmavé téma (myšleno tmavé téma v
systému - testováno na Windows).

Update 4.2.2020
Opravy a doplnění stylů pro dark-mode. Doplněno zjemnění některých barev spojů (červená, zelená, modrá, fialová). Provedeno
sloučení stylů pro idos.cz/cp.sk do jednoho pro zjednodušení. Nový náhledový obrázek.

Update 12.2.2020
Úprava pro CP.sk (změna URL z cpcka.hnonline.sk na cp.hnonline.sk).

Update 29.5.2020
Úprava barvy našeptávače ve světlém tématu (ve tmavém ponechán tmavý).

Update 23.6.2020
Provedena oprava drobné chyby (nedoklep).
Provedeno nakopírování kódu do github.com, takže je styl dostupný na adrese:
https://raw.githubusercontent.com/medvidekBobo/IDOS_Compact/master/IDOS_Compact.user.css

Update 1.7.2020
Provedena drobná oprava kódu pro zobrazení správného znaku nákupního "košíku" z písma Timetable (chybně se zobrazovala negativní osmička).
Ještě doplněno jedno pravidlo pro změnu barvy písma popisku při ukládání karty v dark módu. verze změněna na 1.0.2

Update 3.7.2020
Proveden pokus o doplnění přepínače na použití světlého tématu "vždy světlé téma" (tzn. i když je v systémnu/prohlížeči nastaveno téma tmavé, bude možné zapnout světlé téma).
Doplněny některé parametry v hlavičce stylu (nepodstatné pro funkčnost).

Update 11.9.2020
Doplněna tmavší barva písma u pevných kódu s podbarvením (světle červeným), kde nebyl tento kód čitelný (jedná se o pevné kódy, které nejsou v celé trase spoje).

Update 14.9.2020
Doplněno pravidlo pro přebarvení pevných kódů zobrazovaných za názvy zastávek v dráze spoje (jsou-li vypsány písmem Timetable).

Update 17.9.2020
Drobné úpravy spojené s poslední úpravou IDOS.

Update 30.3.2021
Doplněna úprava výšky našeptávače související s úpravou IDOS.cz. Našeptávač byl
programátory na moji žádost rozšířen z 12 na 18 položek (požadoval jsem víc,
ale nebylo přijato), nicméně jeho výšku (přestože jsem je na to upozornil) nijak
neupravili, takže se moc roztahuje postránce. Tato úprava zavádí omezení jeho
výšky na cca 10 položek a zavedení vertikálního posuvníku, pokud je položek více.
