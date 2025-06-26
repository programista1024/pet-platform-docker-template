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

| Etap | Folder                         | Opis                                       |
|------|--------------------------------|--------------------------------------------|
| 00   | `stage-00-php/`               | Wprowadzenie: PHP + Apache                 |
| 01   | `stage-01-php-mysql/`         | PHP + MySQL (CMS-podobny backend)          |
| 02   | `stage-02-vet-panel-django/`  | Django: panel weterynaryjny                |
| ...  | `...`                         | ...                                        |
| 11   | `stage-11-k8s-deploy/`        | Wdrażanie na Kubernetes                    |

---

## 📦 Jak używać tego szablonu

1. Kliknij przycisk **"Use this template"**
2. Nadaj nazwę repozytorium i widoczność
3. Sklonuj utworzone repo:
   ```bash
   git clone https://github.com/twoja-nazwa/twoje-repo.git
   cd twoje-repo
