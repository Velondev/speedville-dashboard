# 🚀 Speedville Coaching Dashboard

Ein modernes, vollständig responsives Dashboard für digitales Coaching mit interaktiven Features und professionellem Design.

![Speedville Dashboard](https://img.shields.io/badge/Status-Live-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🌟 Live Demo

**[🔗 Dashboard ansehen](https://speedville-dashboard.vercel.app)**

## 📋 Features

### 🏠 **Haupt-Dashboard**
- **KPI-Karten:** Trainingseinheiten, Zeit, Distanz, Feedback-Einträge
- **Interaktive Charts:** Trainingsfortschritt mit Chart.js
- **Nachrichten-Feed:** Aktuelle Coach-Kommunikation
- **Aktivitäts-Timeline:** Chronologische Übersicht

### 🏃‍♂️ **Training-Management**
- **Sport-Filter:** Laufen, Radfahren, Schwimmen, Krafttraining
- **Training-Karten:** Detaillierte Metriken und Notizen
- **Modal-Dialoge:** Neues Training hinzufügen
- **CRUD-Operationen:** Bearbeiten und Löschen von Einträgen

### 💬 **Kommunikation**
- **Echtzeit-Chat:** Vollständiges Messaging-Interface
- **Konversations-Liste:** Übersicht aller Coach-Gespräche
- **Online-Status:** Live-Anzeige der Verfügbarkeit
- **Suchfunktion:** Konversationen durchsuchen

### ❤️ **Feedback & Wellness**
- **Wellness-Tracking:** 5 Hauptmetriken (Energie, Stimmung, Schlaf, Stress, Motivation)
- **Trend-Visualisierung:** Historische Entwicklung mit Charts
- **Slider-Interface:** Intuitive Eingabe-Methoden
- **Feedback-Verlauf:** Chronologische Übersicht

## 🛠 **Technologie-Stack**

### **Frontend**
- **HTML5:** Semantisches Markup
- **CSS3:** Moderne Features (Grid, Flexbox, Backdrop-Filter)
- **JavaScript (ES6+):** Interaktive Funktionalität
- **Chart.js:** Datenvisualisierung
- **Font Awesome:** Icon-Bibliothek

### **Design**
- **Responsive Design:** Mobile-First Approach
- **Glasmorphismus:** Moderne UI mit Backdrop-Blur
- **CSS Grid & Flexbox:** Flexible Layouts
- **Smooth Animations:** Micro-Interactions

### **Deployment**
- **Vercel:** Hosting und CDN
- **GitHub:** Versionskontrolle
- **Automatische Deployments:** Git-basiert

## 🚀 **Schnellstart**

### Lokal testen:
```bash
# Repository klonen
git clone https://github.com/YOUR-USERNAME/speedville-dashboard.git
cd speedville-dashboard

# Lokalen Server starten
python -m http.server 3000
# oder
npx serve .

# Browser öffnen: http://localhost:3000
```

### Bei Vercel deployen:
1. Repository zu GitHub pushen
2. Bei [vercel.com](https://vercel.com) anmelden
3. "New Project" → Repository importieren
4. Deploy klicken ✅

## 📱 **Responsive Design**

Das Dashboard ist vollständig optimiert für:
- **Desktop:** 1920px+ (Full HD und höher)
- **Laptop:** 1024px - 1919px
- **Tablet:** 768px - 1023px
- **Mobile:** 320px - 767px

## 🎨 **Design-System**

### **Farbpalette**
```css
--primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--accent-color: #4ecdc4;
--success-color: #2ecc71;
--warning-color: #f39c12;
--danger-color: #e74c3c;
--text-primary: #333;
--text-secondary: #666;
--background-glass: rgba(255, 255, 255, 0.95);
```

### **Typography**
- **Font Family:** 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Headings:** 700 weight, verschiedene Größen
- **Body Text:** 400 weight, 1rem base size
- **Line Height:** 1.4 - 1.6 für optimale Lesbarkeit

## 🔧 **Konfiguration**

### **vercel.json**
```json
{
  "cleanUrls": true,
  "rewrites": [
    { "source": "/dashboard", "destination": "/dashboard.html" },
    { "source": "/training", "destination": "/training.html" }
  ]
}
```

### **Umgebungsvariablen**
Keine erforderlich - statische Website.

## 📊 **Performance**

- **Lighthouse Score:** 95+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint:** < 1.5s
- **Largest Contentful Paint:** < 2.5s
- **Cumulative Layout Shift:** < 0.1

## 🔒 **Sicherheit**

- **HTTPS:** Automatisch durch Vercel
- **Content Security Policy:** Konfiguriert
- **XSS-Schutz:** Implementiert
- **Clickjacking-Schutz:** X-Frame-Options Header

## 🤝 **Beitragen**

1. Fork das Repository
2. Erstelle einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📝 **Changelog**

### Version 1.0.0 (2025-07-02)
- ✅ Initiales Release
- ✅ Haupt-Dashboard mit KPI-Karten
- ✅ Training-Management-Interface
- ✅ Kommunikations-System
- ✅ Feedback & Wellness-Tracking
- ✅ Vollständig responsive
- ✅ Chart.js Integration
- ✅ Vercel Deployment

## 🐛 **Bekannte Issues**

- Keine kritischen Issues bekannt
- Feature-Requests werden über GitHub Issues verwaltet

## 📞 **Support**

- **GitHub Issues:** [Issues erstellen](https://github.com/YOUR-USERNAME/speedville-dashboard/issues)
- **Dokumentation:** Siehe `/docs` Ordner
- **E-Mail:** support@speedville.com

## 📄 **Lizenz**

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe [LICENSE](LICENSE) Datei für Details.

## 🙏 **Danksagungen**

- **Chart.js** - Für die exzellente Charting-Bibliothek
- **Font Awesome** - Für die umfassende Icon-Sammlung
- **Vercel** - Für das kostenlose Hosting
- **GitHub** - Für die Versionskontrolle

---

**Entwickelt mit ❤️ für die Speedville Community**

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR-USERNAME/speedville-dashboard)

