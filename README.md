# Compass HUD (Fabric 1.21.11)

Ekranın üstünde Call of Duty tarzı yatay pusula çubuğu. Minecraft tooltip görünümünde.

## Derleme

1. Resmi Fabric örnek modundan (https://github.com/FabricMC/fabric-example-mod) `gradlew`, `gradlew.bat` ve `gradle/wrapper/` klasörünü bu klasöre kopyala.
2. `gradle.properties` içindeki sürümleri https://fabricmc.net/develop adresinde 1.21.11 seçerek kontrol et.
3. Çalıştır:
   - `./gradlew runClient` → oyunu test için aç
   - `./gradlew build` → `build/libs/compass-hud-1.0.0.jar`
4. Jar dosyasını `.minecraft/mods` içine at (Fabric Loader + Fabric API gerekli).

## Ayarlar

İlk çalıştırmada `.minecraft/config/compasshud.properties` oluşur:

| Ayar | Açıklama |
|---|---|
| enabled | Pusulayı aç/kapat |
| width | Çubuk genişliği |
| yOffset | Ekran üstünden mesafe |
| pixelsPerDegree | Büyüdükçe daha dar açı gösterir |
| showDegrees | Ortada derece yazısı |
| tooltipStyle | false yaparsan sade yarı saydam siyah panel |
