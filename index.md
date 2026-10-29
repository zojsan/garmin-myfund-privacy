# Polityka prywatności — Garmin MyFund

**Wersja:** 1.0  
**Data obowiązywania:** 28 października 2026 r.  
**Wydawca aplikacji:** `Krzysztof Żukowski`
**Kontakt:** `zojsan@gmail.com`

Przed przesłaniem aplikacji do Connect IQ Store uzupełnij dane wydawcy i
kontaktu, opublikuj tę stronę pod publicznym adresem HTTPS i wklej jej adres
w pole **Privacy Policy URL**. Nie publikuj w tej polityce klucza API ani
danych żadnego portfela.

## Zakres

Garmin MyFund jest nieoficjalnym widgetem Connect IQ do wyświetlania danych
portfela myFund. Aplikacja nie jest powiązana z Garmin ani myFund.

## Jakie dane są używane

Użytkownik może podać w ustawieniach aplikacji klucz API myFund oraz nazwy
maksymalnie trzech portfeli. Aby pobrać podsumowanie, widget przekazuje klucz
API i nazwę wybranego portfela do API myFund. Odpowiedź może zawierać wartość
portfela, walutę, zysk oraz zmiany za wybrane okresy.

Aplikacja zapisuje na zegarku pobrane wartości potrzebne do wyświetlenia
widgetu i glance, nazwy skonfigurowanych portfeli, wybrany portfel oraz status
ostatniego żądania. Dane te są przechowywane lokalnie przez Connect IQ
Application Storage. Ustawienia aplikacji są zarządzane przez Garmin Connect
IQ i synchronizowane z zegarkiem.

## Dokąd są przesyłane dane

Żądanie jest wysyłane bezpośrednio z aplikacji na zegarku do
`https://myfund.pl/API/v1/getPortfel.php`, z użyciem połączenia internetowego
udostępnianego przez Garmin Connect Mobile. Żądanie używa HTTPS. Klucz API
i nazwa portfela są parametrami żądania. Wydawca aplikacji nie prowadzi
serwera pośredniczącego, nie otrzymuje tych żądań ani odpowiedzi i nie zbiera
danych za pomocą telemetrii lub narzędzi analitycznych w aplikacji.

Usługi Garmin oraz myfund.pl uczestniczą w dostarczeniu i obsłudze żądania
zgodnie z własnymi zasadami prywatności. Wydawca nie kontroluje ich praktyk
przechowywania danych ani logowania żądań. myfund.pl informuje o cache'owaniu
odpowiedzi API przez pięć minut; szczegóły przetwarzania przez myfund.pl
podlegają zasadom tego serwisu.

## Klucz API i bezpieczeństwo

Klucz API jest używany do odczytu danych i przesyłany do myfund.pl przez HTTPS.
Ponieważ API przyjmuje klucz jako parametr żądania, jest on dostępny dla
myfund.pl i może podlegać standardowej obsłudze żądań po stronie tego serwisu.
Nie należy traktować go jak sekretu, do którego dostęp ma wyłącznie zegarek.
Wydawca aplikacji nie zapisuje klucza w swoim serwerze ani nie przesyła go do
innych usług.

Chroń telefon i zegarek blokadą ekranu. Jeśli klucz zostanie ujawniony lub
zgubisz urządzenie, unieważnij klucz w myfund.pl i wygeneruj nowy. Aplikacja
nie gwarantuje ochrony przed dostępem osoby, która uzyska dostęp do urządzenia
lub konta Garmin.

## Okres przechowywania i usuwanie

Wydawca aplikacji nie przechowuje danych użytkownika na własnych serwerach.
Ustawienia pozostają w Garmin Connect IQ do czasu ich zmiany lub usunięcia.
Dane odpowiedzi i stan widgetu pozostają w lokalnym magazynie aplikacji na
zegarku, dopóki aplikacja z nich korzysta; można je usunąć, odinstalowując
aplikację lub korzystając z dostępnych w urządzeniu funkcji zarządzania
danymi aplikacji. Zmiana lub usunięcie klucza w ustawieniach nie usuwa
automatycznie kopii danych, które myfund.pl mogło przetworzyć zgodnie z
własnymi zasadami.

## Prawa i kontakt

W sprawach dotyczących danych przetwarzanych przez myfund.pl skontaktuj się
bezpośrednio z myfund.pl. W sprawach dotyczących tej aplikacji skontaktuj się
z wydawcą pod adresem podanym na początku dokumentu.

## Zmiany polityki

W przypadku istotnej zmiany sposobu działania aplikacji lub przetwarzania
danych ta polityka zostanie zaktualizowana, a data obowiązywania zmieniona.

---

# Privacy Policy — Garmin MyFund

**Version:** 1.0  
**Effective date:** 28 October 2026  
**App publisher:** `Krzysztof Zukowski`  
**Contact:** `zojsan@gmail.com`

Before submitting the app to the Connect IQ Store, fill in the publisher and
contact details, publish this page at a public HTTPS address, and enter that
address in the **Privacy Policy URL** field. Do not publish an API key or any
portfolio information in this policy.

## Scope

Garmin MyFund is an unofficial Connect IQ widget that displays myFund
portfolio data. The app is not affiliated with Garmin or myFund.

## Data used

Users may enter a myFund API key and up to three portfolio names in the app
settings. To retrieve a summary, the widget sends the API key and the selected
portfolio name to the myFund API. The response may include the portfolio
value, currency, profit, and changes for selected periods.

The app stores on the watch the retrieved values needed to display the widget
and glance, configured portfolio names, the selected portfolio, and the status
of the most recent request. This data is stored locally using Connect IQ
Application Storage. App settings are managed through Garmin Connect IQ and
synchronized with the watch.

## Where data is sent

The request is sent directly from the watch app to
`https://myfund.pl/API/v1/getPortfel.php`, using the internet connection
provided by Garmin Connect Mobile. The request uses HTTPS. The API key and
portfolio name are request parameters. The app publisher does not operate a
proxy server, receive these requests or responses, or collect data through
in-app telemetry or analytics.

Garmin services and myfund.pl participate in delivering and handling the
request under their own privacy practices. The app publisher does not control
their data-retention or request-logging practices. myfund.pl states that API
responses are cached for five minutes; further processing by myfund.pl is
governed by that service's policies.

## API key and security

The API key is used to read portfolio data and is sent to myfund.pl over
HTTPS. Because the API accepts the key as a request parameter, myfund.pl can
access it and it may be subject to that service's standard request handling.
It should not be treated as a secret accessible only to the watch. The app
publisher does not store the key on a publisher-operated server or send it to
other services.

Protect your phone and watch with a device lock. If your key is exposed or
your device is lost, revoke the key on myfund.pl and generate a new one. The
app cannot guarantee protection against someone who gains access to your
device or Garmin account.

## Retention and deletion

The app publisher does not store user data on publisher-operated servers.
Settings remain in Garmin Connect IQ until changed or removed. Response data
and widget state remain in the app's local storage on the watch while used by
the app; they can be removed by uninstalling the app or using device
application-data management features, where available. Changing or removing
the key in the settings does not automatically delete copies that myfund.pl
may have processed under its own policies.

## Rights and contact

For data processed by myfund.pl, contact myfund.pl directly. For questions
about this app, contact the publisher using the address provided at the
beginning of this document.

## Policy changes

If the app's functionality or data processing changes materially, this
policy will be updated and its effective date changed.
