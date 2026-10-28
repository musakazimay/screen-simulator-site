---
title: Privacy Policy · Gizlilik Politikası
permalink: /privacy/
---

# Screen Simulator — Privacy Policy

_Last updated: 28 October 2026_

Screen Simulator is a Chrome extension for previewing web pages on device-sized screens. It is built so that your data stays on your computer.

## What we collect

Nothing. Screen Simulator has no accounts, no analytics, no advertising and no servers of its own. We do not collect, store, sell or share any personal data, browsing history or page content.

## What stays in your browser

- **Settings:** default devices, saved device sets, custom devices, canvas theme, touch emulation, the MCP on/off switch and the MCP pairing key. They are kept in `chrome.storage` in your browser profile.
- **Simulator state:** which devices a simulator tab shows. It is kept in `chrome.storage` and removed when the tab closes.

## Network connections

- **Your own MCP server (optional):** if you enable the AI-agent feature, the extension connects to `ws://127.0.0.1` (ports 39217–39221) on your own computer. It obeys a server only after both sides prove the pairing key shown on the settings page. Agents only see tabs they opened or that you shared with them.
- **Stylesheets the page already uses:** when a device has its own colour scheme or iOS safe areas, stylesheets the simulated page loads from another website are fetched again, without cookies, so their media queries can be adjusted. A public page is never allowed to make the extension fetch from your local network.
- The extension makes no other connections.

## What the extension changes, and where

Only in the tab where you open the simulator: it adds the device frames, sets each device's user-agent and client-hint headers, removes the page's Content-Security-Policy and X-Frame-Options headers so it can be shown in the device frames, and, in Accurate mode or when a paired agent asks for a screenshot or runs code in a simulated page, attaches Chrome's debugger (Chrome shows a notice bar while it is attached). Other tabs are not touched.

## Contact

Questions about this policy: musakazim.ay@gmail.com

---

# Ekran Simülatörü — Gizlilik Politikası

_Son güncelleme: 28 Ekim 2026_

Ekran Simülatörü, web sayfalarını cihaz boyutundaki ekranlarda önizlemeye yarayan bir Chrome eklentisidir. Verilerinin bilgisayarında kalması için tasarlandı.

## Topladığımız veriler

Hiçbiri. Ekran Simülatörü'nün hesabı, analitiği, reklamı ya da kendine ait sunucusu yoktur. Kişisel veri, gezinme geçmişi ya da sayfa içeriği toplamaz, saklamaz, satmaz ve paylaşmaz.

## Tarayıcında kalanlar

- **Ayarlar:** varsayılan cihazlar, kayıtlı cihaz setleri, özel cihazlar, tuval teması, dokunma taklidi, MCP açma/kapama ve MCP eşleştirme anahtarı. Tarayıcı profilindeki `chrome.storage` içinde tutulur.
- **Simülatör durumu:** bir simülatör sekmesinin hangi cihazları gösterdiği. `chrome.storage` içinde tutulur ve sekme kapanınca silinir.

## Ağ bağlantıları

- **Kendi MCP sunucun (isteğe bağlı):** yapay zekâ ajanı özelliğini açarsan eklenti kendi bilgisayarındaki `ws://127.0.0.1` adresine (39217–39221 portları) bağlanır. Bir sunucuya, iki taraf da ayarlar sayfasındaki eşleştirme anahtarını kanıtlamadan uymaz. Ajanlar yalnızca kendi açtıkları ya da senin paylaştığın sekmeleri görür.
- **Sayfanın zaten kullandığı stil dosyaları:** bir cihaza kendi renk teması ya da iOS güvenli alanları verildiğinde, simüle edilen sayfanın başka sitelerden yüklediği stil dosyaları medya sorgularının uyarlanabilmesi için çerezsiz olarak yeniden çekilir. Herkese açık bir sayfa, eklentiye yerel ağındaki bir adresten dosya çektiremez.
- Eklenti başka bağlantı kurmaz.

## Eklentinin neyi, nerede değiştirdiği

Yalnızca simülatörü açtığın sekmede: cihaz çerçevelerini ekler, her cihazın kullanıcı aracısı ve client hints başlıklarını ayarlar, sayfanın cihaz çerçevesinde gösterilebilmesi için Content-Security-Policy ve X-Frame-Options başlıklarını kaldırır; Birebir modda ya da eşleştirilmiş bir ajan ekran görüntüsü istediğinde veya simüle edilen sayfada kod çalıştırdığında Chrome'un hata ayıklayıcısını bağlar (bağlıyken Chrome bir uyarı çubuğu gösterir). Diğer sekmelere dokunmaz.

## İletişim

Bu politika hakkında sorular: musakazim.ay@gmail.com
