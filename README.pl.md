# 🐾 Platforma dla Zwierząt – Szablon Akademii Dockera

To repozytorium to **szablon projektu edukacyjnego**, który prowadzi przez kolejne etapy konteneryzacji aplikacji webowych z użyciem Dockera. Każdy etap (`stage-XX`) rozwija aplikację o nowe technologie lub usługi.

---

## 🎯 Cel projektu

- Nauka Dockera krok po kroku
- Praca z realistycznym przypadkiem biznesowym
- Budowa złożonej architektury mikroserwisowej
- Praca z różnymi technologiami backendowymi i frontendowymi

---

## 🧠 Koncepcja biznesowa

Modelowa aplikacja to **platforma usług dla zwierząt domowych**, obejmująca:

- 🩺 Usługi weterynaryjne
- ✂️ Grooming / pielęgnacja
- 🏨 Hotel dla zwierząt
- 🚶 Zamawianie wyprowadzacza pupila
- 🐶 Wyszukiwarka schronisk
- 👤 Logowanie i rejestracja użytkowników
- 🎨 Frontend
- 📩 System powiadomień (e-mail, SMS)
- 📈 Monitoring i logowanie
- ☸️ Wdrażanie na Kubernetes

---

## 📁 Struktura folderów (Etapy)

| Etap | Folder                         | Opis                                                                 |
|------|--------------------------------|----------------------------------------------------------------------|
| 00   | `stage-00-php/`               | Wprowadzenie: prosta aplikacja w PHP z Apache                      |
| 01   | `stage-01-php-mysql/`         | PHP + MySQL: prosty backend CMS                                     |
| 02   | `stage-02-vet-panel-django/`  | Django: panel zarządzania usługami weterynaryjnymi                  |
| 03   | `stage-03-grooming-cms/`      | CMS (np. WordPress/Moodle) do obsługi usług pielęgnacyjnych         |
| 04   | `stage-04-hotel-backend/`     | Backend usług hotelarskich dla zwierząt                             |
| 05   | `stage-05-walker-service/`    | Usługa rezerwacji opiekuna do wyprowadzania pupila                 |
| 06   | `stage-06-shelter-search/`    | Wyszukiwarka pobliskich schronisk z geolokalizacją                  |
| 07   | `stage-07-user-auth/`         | System logowania i autoryzacji użytkowników                         |
| 08   | `stage-08-frontend-react/`    | Frontend aplikacji w React                                          |
| 09   | `stage-09-email-service/`     | Mikrousługa wysyłania powiadomień e-mailowych                       |
| 10   | `stage-10-monitoring/`        | Monitoring, metryki, logowanie (np. Prometheus + Grafana)           |
| 11   | `stage-11-k8s-deploy/`        | Wdrażanie usług na Kubernetes (Helm, manifesty, ingress itd.)       |

---

## 📦 Jak używać tego szablonu

1. Kliknij przycisk **"Use this template"**
2. Nadaj nazwę repozytorium i widoczność
3. Sklonuj utworzone repo:
   ```bash
   git clone https://github.com/twoja-nazwa/twoje-repo.git
   cd twoje-repo

---

## 🛠 Wymagania

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Docker Compose](https://docs.docker.com/compose/)
- (Opcjonalnie) [GPG – podpisywanie commitów](https://docs.github.com/pl/authentication/managing-commit-signature-verification)
- (Opcjonalnie) [Visual Studio Code](https://code.visualstudio.com/) z rozszerzeniami Docker i Dev Containers

---

## 📚 Dokumentacja

Zobacz [`docs/architecture.md`](docs/architecture.md), gdzie znajdziesz:

- Ogólną architekturę systemu
- Strategię integracji usług
- Wskazówki dotyczące kontrybucji
- Wzorce projektowe i granice modułów

---

## 🤝 Współpraca

Projekt jest otwarty na wszelkie formy współpracy, w tym:

- Udoskonalanie plików Dockerfile i konfiguracji
- Dodawanie lub dokumentowanie kolejnych etapów (`stage-*`)
- Tworzenie tutoriali i plików README
- Dodawanie testów i automatyzacji (GitHub Actions)

Jak współpracować:
1. Sforkuj repozytorium
2. Utwórz nową gałąź z `main`
3. Złóż Pull Request z jasnym opisem zmian

---

## 📄 Licencja

Ten projekt jest objęty licencją **Apache License 2.0**.
Wszystkie prace pochodne (np. akademie oparte na tym szablonie) **muszą zachować tę licencję** oraz wskazanie oryginalnego autora.
Szczegóły znajdują się w plikach [`LICENSE`](LICENSE) i [`NOTICE`](NOTICE).

---

Projekt tworzony z ❤️ przez [Programista1024.pl](https://programista1024.pl)