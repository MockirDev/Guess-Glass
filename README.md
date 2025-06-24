# 🎮 Guess Glass - Cam Atlama Oyunu

[English](#english) | [Deutsch](#deutsch) | [Türkçe](#türkçe)

---

## Türkçe

### 📱 Oyun Hakkında

**Guess Glass**, Flutter ile geliştirilmiş heyecan verici bir mobil oyundur. Oyuncular, karşılarına çıkan üç camdan doğru olanını seçerek bir sonraki seviyeye geçmeye çalışır. Yanlış seçim yapılırsa cam kırılır ve oyuncu düşer!

### ✨ Özellikler

- **🌍 Çok Dilli Destek**: Türkçe, İngilizce, Fransızca, Almanca
- **🎯 Sonsuz Oynanabilirlik**: Maksimum seviye yok, sürekli zorlaşan gameplay
- **🎨 Tema Desteği**: Açık ve koyu tema seçenekleri
- **🃏 Joker Sistemi**: 3 farklı joker türü ile stratejik oyun
- **📍 Checkpoint Sistemi**: Her 50 seviyede otomatik kayıt
- **🎵 Ses ve Titreşim**: Ayarlanabilir ses efektleri ve titreşim
- **📱 Reklam Entegrasyonu**: Google AdMob ile banner ve ödüllü reklamlar
- **🎓 Oyun İçi Rehber**: Yeni oyuncular için detaylı tanıtım

### 🎮 Oyun Mekaniği

#### Temel Oynanış
- Her seviyede 3 cam bulunur, sadece 1'i sağlamdır
- 20 saniye içinde seçim yapılmalıdır
- Doğru seçim: Bir sonraki seviyeye geçiş
- Yanlış seçim: Cam kırılır ve en son checkpoint'e dönüş

#### Zorluk Seviyeleri
- **1-25 Seviye**: Normal - Yanlış camlar anında kırılır
- **26-50 Seviye**: Gecikmeli - Camlar birkaç milisaniye sonra kırılır
- **51-75 Seviye**: Daha Gecikmeli - Daha uzun gecikme
- **76-100 Seviye**: Çatlak Camlar - Görsel olarak çatlak camlar
- **101-125 Seviye**: Çok Gecikmeli - Maksimum gecikme
- **126+ Seviye**: Sahte Dayanıklılık - Camlar ilk temasta kırılmaz gibi görünür

#### Joker Türleri
1. **🔍 Doğru Camı Göster**: Hangi camın sağlam olduğunu gösterir
2. **💾 Checkpoint Oluştur**: Mevcut seviyeyi checkpoint yapar (25. seviyeden sonra)
3. **⏸️ Zamanı Dondur**: 20 saniyelik süreyi durdurur

### 🛠️ Teknik Özellikler

#### Kullanılan Teknolojiler
- **Framework**: Flutter 3.7.0+
- **Dil**: Dart
- **State Management**: Provider
- **Yerelleştirme**: Flutter Intl
- **Reklamlar**: Google Mobile Ads
- **Veri Saklama**: SharedPreferences

### 🎯 Oyun Stratejisi

#### Benzersiz Cam Dizilimi
- Her oyuncu için benzersiz cam dizilimi oluşturulur
- Dizilim cihazda şifreli olarak saklanır
- Oyunu silip tekrar kursa bile aynı dizilim korunur
- Bu sayede oyuncular strateji geliştirebilir ama başkalarının stratejilerini kopyalayamaz

### 📱 Platform Desteği

- ✅ Android (API 21+)
- ✅ iOS (iOS 12+)
- ⚠️ Web (Sınırlı destek)
- ⚠️ Desktop (Deneysel)

### 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

---

## English

### 📱 About the Game

**Guess Glass** is an exciting mobile game developed with Flutter. Players try to advance to the next level by choosing the correct glass from three glasses in front of them. If you make the wrong choice, the glass breaks and the player falls!

### ✨ Features

- **🌍 Multi-language Support**: Turkish, English, French, German
- **🎯 Infinite Gameplay**: No maximum level, continuously challenging gameplay
- **🎨 Theme Support**: Light and dark theme options
- **🃏 Joker System**: Strategic gameplay with 3 different joker types
- **📍 Checkpoint System**: Automatic save every 50 levels
- **🎵 Sound and Vibration**: Adjustable sound effects and vibration
- **📱 Ad Integration**: Banner and rewarded ads with Google AdMob
- **🎓 In-Game Tutorial**: Detailed guide for new players

### 🎮 Game Mechanics

#### Basic Gameplay
- Each level has 3 glasses, only 1 is solid
- Must make a choice within 20 seconds
- Correct choice: Advance to next level
- Wrong choice: Glass breaks and return to last checkpoint

#### Difficulty Levels
- **Levels 1-25**: Normal - Wrong glasses break instantly
- **Levels 26-50**: Delayed - Glasses break after a few milliseconds
- **Levels 51-75**: More Delayed - Longer delay
- **Levels 76-100**: Cracked Glasses - Visually cracked glasses
- **Levels 101-125**: Very Delayed - Maximum delay
- **Levels 126+**: Fake Durability - Glasses appear not to break on first contact

#### Joker Types
1. **🔍 Show Correct Glass**: Shows which glass is solid
2. **💾 Create Checkpoint**: Makes current level a checkpoint (after level 25)
3. **⏸️ Freeze Time**: Stops the 20-second timer

### 🛠️ Technical Features

#### Technologies Used
- **Framework**: Flutter 3.7.0+
- **Language**: Dart
- **State Management**: Provider
- **Localization**: Flutter Intl
- **Ads**: Google Mobile Ads
- **Data Storage**: SharedPreferences

### 🎯 Game Strategy

#### Unique Glass Sequence
- A unique glass sequence is generated for each player
- The sequence is stored encrypted on the device
- The same sequence is preserved even if the game is deleted and reinstalled
- This allows players to develop strategies but prevents copying others' strategies

### 📱 Platform Support

- ✅ Android (API 21+)
- ✅ iOS (iOS 12+)
- ⚠️ Web (Limited support)
- ⚠️ Desktop (Experimental)

### 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Deutsch

### 📱 Über das Spiel

**Guess Glass** ist ein aufregendes Handyspiel, das mit Flutter entwickelt wurde. Die Spieler versuchen, das nächste Level zu erreichen, indem sie das richtige Glas aus drei Gläsern vor sich auswählen. Bei einer falschen Wahl zerbricht das Glas und der Spieler fällt!

### ✨ Funktionen

- **🌍 Mehrsprachige Unterstützung**: Türkisch, Englisch, Französisch, Deutsch
- **🎯 Unendliches Gameplay**: Kein maximales Level, kontinuierlich herausforderndes Gameplay
- **🎨 Theme-Unterstützung**: Helle und dunkle Theme-Optionen
- **🃏 Joker-System**: Strategisches Gameplay mit 3 verschiedenen Joker-Typen
- **📍 Checkpoint-System**: Automatische Speicherung alle 50 Level
- **🎵 Sound und Vibration**: Einstellbare Soundeffekte und Vibration
- **📱 Werbe-Integration**: Banner- und Belohnungswerbung mit Google AdMob
- **🎓 In-Game-Tutorial**: Detaillierte Anleitung für neue Spieler

### 🎮 Spielmechanik

#### Grundlegendes Gameplay
- Jedes Level hat 3 Gläser, nur 1 ist stabil
- Muss innerhalb von 20 Sekunden eine Wahl treffen
- Richtige Wahl: Zum nächsten Level vorrücken
- Falsche Wahl: Glas zerbricht und Rückkehr zum letzten Checkpoint

#### Schwierigkeitsgrade
- **Level 1-25**: Normal - Falsche Gläser zerbrechen sofort
- **Level 26-50**: Verzögert - Gläser zerbrechen nach einigen Millisekunden
- **Level 51-75**: Mehr verzögert - Längere Verzögerung
- **Level 76-100**: Rissige Gläser - Visuell rissige Gläser
- **Level 101-125**: Sehr verzögert - Maximale Verzögerung
- **Level 126+**: Falsche Haltbarkeit - Gläser scheinen beim ersten Kontakt nicht zu zerbrechen

#### Joker-Typen
1. **🔍 Richtiges Glas zeigen**: Zeigt, welches Glas stabil ist
2. **💾 Checkpoint erstellen**: Macht das aktuelle Level zu einem Checkpoint (nach Level 25)
3. **⏸️ Zeit einfrieren**: Stoppt den 20-Sekunden-Timer

### 🛠️ Technische Funktionen

#### Verwendete Technologien
- **Framework**: Flutter 3.7.0+
- **Sprache**: Dart
- **State Management**: Provider
- **Lokalisierung**: Flutter Intl
- **Werbung**: Google Mobile Ads
- **Datenspeicherung**: SharedPreferences

### 🎯 Spielstrategie

#### Einzigartige Glassequenz
- Für jeden Spieler wird eine einzigartige Glassequenz generiert
- Die Sequenz wird verschlüsselt auf dem Gerät gespeichert
- Dieselbe Sequenz bleibt erhalten, auch wenn das Spiel gelöscht und neu installiert wird
- Dies ermöglicht es Spielern, Strategien zu entwickeln, verhindert aber das Kopieren der Strategien anderer

### 📱 Plattform-Unterstützung

- ✅ Android (API 21+)
- ✅ iOS (iOS 12+)
- ⚠️ Web (Begrenzte Unterstützung)
- ⚠️ Desktop (Experimentell)

### 📄 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Siehe die `LICENSE`-Datei für Details.

---

## 📸 Screenshots

*Screenshots will be added soon...*

## 🔗 Links

- [Google Play Store](#) *(Coming Soon)*
- [App Store](#) *(Coming Soon)*

## 👨‍💻 Developer

Developed with MockirDev using Flutter

---

**Version**: 1.0.3+4  
**Last Updated**: June 2025
