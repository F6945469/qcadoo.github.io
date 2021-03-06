---
title: "Rejestracja produkcji"
permalink: rejestracja-produkcji.html
---
Funkcja ta służy do gromadzenia informacji zwrotnych zebranych na hali produkcyjnej, dających obraz postępów w realizacji zleceń (tzw. meldunki zwrotne).
  
W qcadoo rejestrowanie przebiegu produkcji odbywa się na jednym z trzech poziomów (szerszy opis w osobnych artykułach):

- [podstawowy](/podstawowe-rejestrowanie-produkcji) - zbieramy dane o **ilości** pobranych i skonsumowanych produktów w zleceniu,
- [zbiorczy](/zbiorcze-rejestrowanie-produkcji)- rejestrujemy **czas pracy** (pracowników i maszyn) nad danym zleceniem **oraz ilości** produktów w tym czasie użytych,
- [dla każdej operacji](/rejestracja-kazdej-operacji) - dokładniejszy od zbiorczego, **czas pracy i ilości produktów** rejestrowane są w ramach **każdej operacji.** 

## Jak rejestrować produkcję i wprowadzać meldunki zwrotne?

Aby wykonać rejestrację produkcji w qcadoo przy zakładaniu nowego **zlecenia produkcyjnego (PLANOWANIE Planowanie zleceń)**, w karcie **Rejestracja produkcji** należy wybrać interesujący nas sposób zbierania danych.

Sposoby rejestracji meldunków: **Zbiorczy** i **Dla każdej operacji** dają możliwość określenia czy (pole po lewej stronie):

- rejestrujemy produkty wejściowe i wyjściowe
- czy rejestrujemy czasy produkcji

Parametry te, według uznania, mogą być pominięte w formularzu rejestracji produkcji.

{% include lightbox.html file="planowanie-%20rejestracja%20produkcji.png" alt="Parametry rejestracji produkcji" caption="Parametry rejestracji produkcji" %}
  
Parametry widoczne po prawej stronie:

- **Jeden meldunek zbiorczy lub jeden dla każdej operacji** - jeśli zaznaczymy to pole: przy rejestracji produkcji w danym zleceniu możliwe będzie wprowadzenie JEDNEGO raportu zbiorczego lub po JEDNYM meldunku dla każdej operacji.
- **Pozwól na zamknięcie zlecenia tylko, jeśli został wprowadzony ostatni meldunek zwrotny** - System będzie pilnował, by zlecenie produkcyjne nie zostało zamknięte bez ostatniego meldunku zwrotnego
- **Ostatni meldunek zamyka automatycznie zlecenie** - Wprowadzenie ostatniego meldunku zwrotnego będzie jednoznacznie kończyło zlecenie produkcyjne.

{% include callout.html content="Jeśli przy **Rejestracji produkcji** chcemy zawsze gromadzić te same dane, to w **Administracji** (pozycja menu) należy wybrać **Parametry**, a następnie zakładkę **Rejestracja produkcji** i zaznaczyć interesujące nas preferencje." type="info" %} 

## Aby wprowadzić meldunek zwrotny wybierz:

**REJESTRACJA >> Rejestracja produkcji >> {% include inline_image.html file="newIcon24.png" alt="Przycisk Dodaj nowe zlecenie" %} Dodaj nowy**

{% include lightbox.html file="rejestracja-%20rejestracja%20produkcji.png" alt="Rejestracja produkcji" caption="Rejestracja produkcji" %}

1. W pierwszym kroku przy użyciu {% include inline_image.html file="lupka.png" %} wybieramy "Zlecenie produkcyjne", które chcemy zarejestrować. Po wybraniu zlecenia, pole "Linia produkcyjna" wypełni się automatycznie.

2. Następnie, jeżeli wybraliśmy sposób rejestracji meldunku "dla każdej operacji", należy wybrać "Operację". W przypadku rejestracji w sposób podstawowy bądź zbiorczy pole to pozostaje niewidoczne.

3. {% include inline_image.html file="zapisz.png" alt="Przycisk Zapisz" %} **Zapisz**. Po zapisaniu danych uaktywnią nam się dane w następnej karcie **Produkty we./wyj.**

{% include lightbox.html file="rejestracja%20produkcji%20produkty%20wej%C5%9Bcia-%20wyj%C5%9Bcia.png" alt="Rejestracja produkcji - produkty" caption="Rejestracja produkcji - produkty" %}  

4. Kolejno należy wypełnić dane dotyczące ilości zużytych materiałów("Podana ilość"). Informacje te możemy wprowadzić ręcznie w oparciu o otrzymane z hali produkcyjnej karty pracy (meldunki zwrotne) lub skopiować ilości z planowanych {% include inline_image.html file="copyIcon24.png" alt="Przycisk Kopiuj" %}  
  
5. Ponownie zapisujemy dane {% include inline_image.html file="zapisz.png" alt="Przycisk Zapisz" %} **Zapisz** i przechodzimy do następnej zakładki **Czas pracy** , gdzie będziemy rejestrować czas pracy maszyn oraz pracowników.

Po wprowadzeniu i zapisaniu wszystkich informacji możemy zaakceptować taki meldunek. Aby to zrobić wybieramy przycisk {% include inline_image.html file="startIcon24.png" alt="Przycisk Zapisz" %} **Akceptuj**, wówczas nie możemy już wprowadzać żadnych zmian. 

Jeżeli dany meldunek jest ostatnim meldunkiem wprowadzanym dla danej operacji bądź zlecenia, w zakładce **"Główna"** zaznaczamy "Końcowy".

