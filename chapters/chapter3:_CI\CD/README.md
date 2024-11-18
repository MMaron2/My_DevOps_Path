# CI vs CD

Continuous Integration (CI) i Continuous Delivery/Deployment (CD) to kluczowe praktyki w nowoczesnym cyklu życia oprogramowania. Choć są powiązane, mają różne cele i zakres działań.

## Continuous Integration (CI)

**Cel:** Automatyczne łączenie kodu i weryfikacja, czy integracje są poprawne.

- **Definicja:**  
  CI polega na częstym łączeniu zmian w kodzie z główną gałęzią repozytorium. Zmiany te są automatycznie testowane, aby upewnić się, że nowy kod nie psuje istniejącej funkcjonalności.

- **Elementy charakterystyczne:**
  - Automatyczne budowanie aplikacji po każdej zmianie w kodzie.
  - Uruchamianie testów jednostkowych i integracyjnych.
  - Szybkie identyfikowanie błędów w kodzie.

- **Korzyści:**
  - Redukcja problemów związanych z integracją kodu od wielu programistów.
  - Wczesne wykrywanie błędów, co obniża koszty ich naprawy.

---

## Continuous Delivery (CD)

**Cel:** Przygotowanie oprogramowania do wydania w każdej chwili.

- **Definicja:**  
  CD rozszerza CI, automatyzując proces wdrażania kodu na środowiska testowe i produkcyjne. Kluczowe jest tu ręczne zatwierdzanie wdrożenia na produkcję.

- **Elementy charakterystyczne:**
  - Automatyczne wdrażanie kodu na środowiska testowe lub staging.
  - Możliwość wydania działającego oprogramowania w dowolnym momencie.
  - Automatyczne testy akceptacyjne i end-to-end.

- **Korzyści:**
  - Skrócenie czasu potrzebnego na wdrożenie nowych funkcji.
  - Zwiększenie pewności, że oprogramowanie działa poprawnie na każdym etapie.

---

## Continuous Deployment (CD)

**Cel:** Automatyczne wdrażanie każdej zmiany kodu na środowisko produkcyjne.

- **Definicja:**  
  Continuous Deployment automatyzuje cały proces wdrażania na produkcję. Zatwierdzenie zmiany w repozytorium kodu automatycznie powoduje wdrożenie jej na środowisko produkcyjne.

- **Elementy charakterystyczne:**
  - Brak ręcznego zatwierdzania wdrożeń na produkcję.
  - Wysoki poziom automatyzacji i zaufania do testów.

- **Korzyści:**
  - Szybkie dostarczanie wartości dla użytkowników końcowych.
  - Eliminacja opóźnień związanych z ręcznym procesem wdrażania.

---

## Podsumowanie różnic

| Cecha                  | Continuous Integration (CI)  | Continuous Delivery (CD)       | Continuous Deployment (CD)     |
|------------------------|-----------------------------|--------------------------------|---------------------------------|
| **Cel**               | Integracja kodu i testowanie | Gotowość do wydania            | Automatyczne wydanie na produkcję |
| **Automatyzacja**     | Budowanie i testowanie       | Budowanie, testowanie, wdrażanie na staging | Budowanie, testowanie, wdrażanie na produkcję |
| **Ręczna interwencja**| Wymagana tylko przy kodowaniu | Wymagana przy wydaniu na produkcję | Nie jest wymagana              |
| **Zastosowanie**      | Codzienna praca zespołów    | Testowanie i przegląd zmian    | Dynamiczne środowiska produkcyjne |

