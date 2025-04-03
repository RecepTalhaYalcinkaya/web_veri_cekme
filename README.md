Kod, Science Robotics sayfasındaki makale başlıklarını çekerek makaleler.xlsx isimli bir Excel dosyasına kaydedecektir.
Kod ayrıca bir sonraki sayfanın bağlantısını alıp ekrana yazdırır ve tarayıcıyı bu sayfaya yönlendirir.

Çalışma Prensibi:
Selenium ile hedef sayfa açılır ve sayfanın HTML içeriği alınır.
BeautifulSoup ile sayfa parse edilerek makale başlıkları seçilir.
Pandas ile başlıklar bir DataFrame'e dönüştürülerek Excel dosyasına kaydedilir.
Eğer sayfada "Sonraki Sayfa" düğmesi varsa, bağlantısı çekilir ve bir sonraki sayfa yüklenir.
Tarayıcı oturumu kapatılır.
