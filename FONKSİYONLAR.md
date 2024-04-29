# Fonskiyonel komutlar ve yardımcılar. (TURKISH)

PERSONAL/CORPORATE SYSTEM TWEAKS FOR WINDOWS (TURKISH)

Fonksiyonel komutlar ve yardımcılar:

cmd > winsat formal = sistemi stres testine sokar ve sistemi puanlar.
cmd > powercfg /energy = güç sorunları, powercfg /hibernate on = o anki oturumu ram yerine diskte tutar
cmd > attrib +s +h %USERPROFILE%/Desktop/Gizli = dosyayı gizler. sadece path ile erişlebilir. geri almak için: -s -h.
cmd > fsutil file createNew %USERPROFILE%/Desktop/thefile.txt 32000000000 = 32 gb'lık txt dosyası oluşturur.
cmd > takeown /f C:\Users\Umut\Desktop/Gizli = aitliğini al
cmd > xcopy source [HEDEF] = detaylı kopyalama ve backup aracı.

text dosyasının başına .LOG koyarsan textteki değişiklikleri tarih saat atar.

cmd > systeminfo = pc bilgileri
cmd > msinfo32 = daha detaylı pc bilgileri
dxdiag > pc özeti
cmd > assoc = hangi dosya uzantılarının hangi programa ait olduğun
cmd > netplwiz = kullanıcıları düzenle
mmc = kendine ait konsol oluşturur
gpedit.msc = group policy editor
secpol.msc = security policy editor
ncpa.cpl = network adaptörleri
cmd > stasklist /svc = çalışan servislerin detayları
cmd > taskkill /f /im chrome.exe = chrome'u öldür

ipconfig /release = dhcp salar 
ipconfig /renew = yeni ip atar
ipconfig /flushdns = dns cache'ini boşalatır

tracert google.com = nereye gittiğine bakar
pathping google.com = daha fazla tracert istatistiği

net share = paylaşılan klasörleri gösterir

telnet aardmud.org = telnet açar (ipnin portunu yoklar)

Rundll32.exe advapi32.dll, ProcessIdleTasks = boşta çalışırken bakım yapar.

net use = ağda disk var mı?
net use /del * = ağdaki diskleri sil.
