# Modulacje  

## Czym jest modulacja?  

Modulacją w technice nazywa się celowy proces zmiany parametrów fali nośnej umożliwiający przesyłanie informacji.  
<br/>  

## Modulacje techniki kluczowania:  

(troszkę historii)  

Kluczowanie (ang. keying) jest najstarszą techniką modulacji. Kiedy w XIX wieku zbudowano pierwsze elektryczne urządzenia do przekazywania informacji na odległość, pojawił się problem kodowania znaków do postaci nadającej się do przesłania. Pierwszym pomysłem było użycie tylu przewodów, ile jest liter w alfabecie. Pomysł ten okazał się niepraktyczny i dlatego Samuel Morse stworzył system kodowania znaków alfabetu w postaci serii krótkich (kropka) lub długich (kreska) impulsów. Urządzeniem kodującym był klucz mający postać przełącznika zwierającego obwód elektryczny. Operator wysyłał serię impulsów, którą odczytywał człowiek lub elektromagnes zapisywał na papierowej taśmie. Kiedy technologia transmisji się rozwinęła, powstał szereg technik kluczowania. Potem wszystkie te metody określono jednym terminem – modulacja.

## Modulacja ASK:  
czyli **A**mplitude-**S**hift **K**eying  

<img src=data/modulacja_ask.jpg alt="isolated" width=""/>  

<br/>  

### Jak działa modulacja ASK?  
W modulacji ASK, dane cyfrowe są kodowane jako dwie różne wartości amplitudy sygnału nośnego. W jednym przypadku, nośna może mieć wysoką amplitudę (oznaczającą wartość logiczną "1"), a w drugim przypadku może mieć niską amplitudę (oznaczającą wartość logiczną "0").  

<br/>  

### Gdzie się stosuje ASK?  
Modulacja ta stosowana jest np. w:  
-przewodowe sieci komputerowe (Ethernet)  
-telewizja cyfrowa  
-RFID  
-modemy linii telefonicznych  

<br/>  

## Modulacja PSK:  
**P**hase-**S**hift **K**eying  

<img src=data/psk.png alt="isolated" width=350/>  

<br/>  

### Jak działa modulacja PSK?  
Dane cyfrowe są kodowane w postaci różnych wartości faz sygnału nośnego. Na przykład, w przypadku BPSK, dwie wartości faz są używane do kodowania dwóch wartości logicznych, np. 0 i 1. W przypadku QPSK, cztery wartości faz są używane do kodowania czterech wartości logicznych.  

<br/>  

### Gdzie się stosuje PSK?  
Modulacja ta stosowana jest np. w:  
-komunikacja satelitarna  
-komunikacja światłowodowa  
-systemy telewizji cyfrowej  
-systemy bezprzewodowe (GSM, Wi-Fi, Bluetooth)  

<br/>  

## Modulacja FSK:  
**F**requency-**S**hift **K**eying  

<img src=data/fsk.png alt="isolated" width=350/>  

<br/>  

### Jak działa modulacja FSK?  
Sytuacja **analogiczna** do modulacji ASK  

Reprezentacja danych odbywa się poprzez zmiany częstotliwości fali nośnej. Przy stałej amplitudzie harmonicznego sygnału nośnego następuje zmiana częstotliwości: niższa reprezentuje symbol logicznego „0” informacji binarnej, a wyższa częstotliwość – logicznej „1”. Czasami przypisanie częstotliwości może być odwrotne. 

<br/>  

### Gdzie się stosuje FSK?  
Modulacja ta stosowana jest np. w:  
-radiotelefony  
-telewizja cyfrowa  
-RFID  
-modemy linii telefonicznych  
-systemy bezprzewodowe (krótkiego zasięgu)  

<br/>  


## Modulacja QAM:  
**Q**uadrature **A**mplitude **M**odulation  

<img src=data/qam.gif alt="isolated" width=350/>  

<br/>  

### Jak działa modulacja QAM?  
W QAM, dane cyfrowe są kodowane jako kombinacja amplitudy i fazy nośnej fali. Sygnał nośny jest podzielony na dwa lub więcej równoległych kanałów, które są przesunięte fazowo względem siebie. Każdy z tych kanałów może mieć różną amplitudę, co umożliwia kodowanie większej ilości informacji w jednym symbolu.  

<br/>  

### Gdzie się stosuje QAM?  
Modulacja ta stosowana jest np. w:  
-telekomunikacja szerokopasmowa (DSL i kablówka)  
-telewizja cyfrowa (DVB)  
-przewodowe sieci komputerowe (Ethernet)  
-modemy linii telefonicznych  
-systemy satelitarne

<br/>  

# Podsumowanie:  

1. ASK (Amplitude Shift Keying):
- Moduluje informację przez zmiany amplitudy nośnej fali.
- Prosta do zrozumienia i zaimplementowania.
- Wrażliwa na zakłócenia i szumy, ponieważ zmiany amplitudy są bardziej podatne na zniekształcenia.
- Stosowana w systemach, gdzie priorytetem jest prostota implementacji, a nie przepływność lub odporność na zakłócenia.
2. PSK (Phase Shift Keying):
- Moduluje informację przez zmiany fazy nośnej fali.
- Odporna na zakłócenia w porównaniu do ASK.
- Wymaga precyzyjnej synchronizacji fazowej między nadajnikiem i odbiornikiem.
- Stosowana w systemach, gdzie istotne jest utrzymanie stabilnej fazy, takich jak systemy telekomunikacyjne i transmisja danych.
3. FSK (Frequency Shift Keying):
- Moduluje informację przez zmiany częstotliwości nośnej fali.
- Może być stosowana w systemach o większej odporności na zakłócenia w porównaniu do ASK i PSK.
- Wymaga większej szerokości pasma transmisyjnego ze względu na konieczność zmiany częstotliwości.
- Stosowana w systemach RFID, radiotelemetrii, radiopagerach i niektórych systemach bezprzewodowych.
4. QAM (Quadrature Amplitude Modulation):
- Kombinuje modulację amplitudy (ASK) i modulację fazy (PSK).
- Pozwala na przesyłanie większej ilości danych cyfrowych w jednym symbolu.
- Wysoka przepływność i efektywność transmisji.
- Stosowana w telekomunikacji szerokopasmowej, telewizji cyfrowej, sieciach komputerowych, systemach bezprzewodowych i komunikacji satelitarnej.  

Podsumowując, każdy z tych systemów modulacji ma swoje unikalne właściwości i zastosowania. ASK jest prostsze do zrozumienia i implementacji, PSK jest bardziej odporna na zakłócenia, FSK znajduje zastosowanie w systemach RFID i telemetrii, a QAM pozwala na przesyłanie większej ilości danych w jednym symbolu i jest szeroko stosowana w różnych systemach komunikacji cyfrowej.


