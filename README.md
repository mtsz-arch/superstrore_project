# 📊 Analiza sprzedaży i rentowności firmy e-commerce

Analiza danych sprzedażowych firmy **SuperStore** obejmująca czyszczenie danych, eksploracyjną analizę danych (EDA), feature engineering oraz budowę interaktywnego dashboardu w Power BI.

---

## Cele projektu

-  Analiza trendów sprzedażowych i rentowności  
- Segmentacja geograficzna i rynkowa  
- Profilowanie klientów według zachowań zakupowych  
- Optymalizacja procesów wysyłki  
- Stworzenie interaktywnego dashboardu do monitorowania KPI  

---

## 🛠️ Technologie

### Python & Biblioteki

- **pandas** – manipulacja i analiza danych  
- **matplotlib** – wizualizacja danych  
- **NumPy** – operacje numeryczne  
- **Google Colab** – środowisko deweloperskie  

### Business Intelligence

- **Power BI** – interaktywne dashboardy i raporty  

---

##  1. Przygotowanie danych

- Import i walidacja danych ze źródła `SuperStoreOrders.csv`

- Konwersja typów danych (numeryczne, kategoryczne, daty)

- Standaryzacja formatów liczbowych (obsługa separatorów tysięcznych)
- wstępne insight'y 
<img width="1912" height="816" alt="obraz" src="https://github.com/user-attachments/assets/b1274fc8-952a-41e1-a5da-71a4061d4e9f" />
<img width="1912" height="633" alt="obraz" src="https://github.com/user-attachments/assets/5dc38b11-0758-4aa9-9531-a0f5687df85e" />
<img width="1853" height="255" alt="obraz" src="https://github.com/user-attachments/assets/7d92923d-fe34-4ca6-91ca-2f38bf208cb1" />
<img width="1187" height="580" alt="obraz" src="https://github.com/user-attachments/assets/1c7d525a-0738-4b5e-8e61-8ce2226a9902" />
parę z tych operacji zostanie wykonana ponownie w środowisku PowerBI, te insght'y służą jako walidacja o niepopełnieniu błędu w miarach.
---

## ⚙️ 2. Feature Engineering

### Nowe zmienne analityczne:
- `order_year` – rok zamówienia  
- `order_month` – miesiąc zamówienia  
- `order_quarter` – kwartał zamówienia  
- `profit_margin` – marża zysku
- `customer segment` – "Low Value", "Medium Value", " High Value", "VIP"
- `DayOfWeek` – dzien tygodnia
- `YearMonth` – Rok i miesiąc zamówienia


## 🔍 3. Przeprowadzone analizy

### 📈 Analiza sprzedaży i zyskowności

- Identyfikacja produktów i kategorii o najwyższej sprzedaży  
- Analiza marż i rentowności  
- Wykrywanie produktów stratnych  

### 🌍 Segmentacja geograficzna

- Podział na regiony i rynki  
- Analiza wydajności według kraju  
- Mapowanie geograficzne sprzedaży  

### ⏱️ Analiza czasowa

- Trendy sprzedażowe w czasie  
- Sezonowość sprzedaży  
- Analiza wzorców zakupowych  

### 🚚 Optymalizacja wysyłki

- Średnie czasy dostawy według metody wysyłki  
- Analiza kosztów wysyłki  
- Priorytetyzacja zamówień  

### 👥 Segmentacja klientów

- Podział na segmenty (*Consumer, Corporate, Home Office*)  
- Analiza zachowań zakupowych    

### 🔗 Analiza korelacji

- Badanie zależności między zmiennymi  
- Identyfikacja kluczowych czynników wpływających na zysk  
- Analiza wpływu rabatów na rentowność  

---

## 📊 Wizualizacje

Dashboard w **Power BI** zawiera:
<img width="1181" height="657" alt="obraz" src="https://github.com/user-attachments/assets/89826c3e-da21-46ac-bc62-692ee2fb0486" />
<img width="1178" height="656" alt="obraz" src="https://github.com/user-attachments/assets/54e6ec96-ece9-4634-96c6-5cc806f60f35" />
<img width="1180" height="661" alt="obraz" src="https://github.com/user-attachments/assets/86d20b57-ebc6-443c-8563-b87db60bbb42" />

- 📉 Trendy sprzedażowe i zyskowności w czasie  
- 🗺️ Mapy geograficzne wydajności sprzedaży  
- 📊 Wykresy porównawcze produktów i kategorii  
- 🎯 KPI i metryki biznesowe  
- 🔍 Interaktywne filtry i slicery  



---

## 🧠 Wyniki – kluczowe insighty

### 💰 Rentowność produktów

- Kategoriami z najwyższą marżą są Office Supplies i Technology
- Jedynym produktem generującym stratę jest  Eureka Disposable Bags for Sanitaire Vibra Groomer 

### 🌍 Segmentacja geograficzna

- Najlepiej dochodowym krajem są Stany Zjednoczone 
- Obszarem wymagającym dodatkowej uwagi jest Kanada, ma najniższą ilość sprzedaży

### ⚙️ Optymalizacja procesów

- Największa mediana czasu wysyłki jest w klasie standardowej, czyli tej najpopularniejszej 

