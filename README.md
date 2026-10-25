# Kod_asistanim Ayşenur Saygılı
## Projenin amacı:Kullanıcılara günlük işlerde hesaplama selamlama vb. yardımcı olacak bir dijital asistan tasarlamak.
## Projenin hedefleri:Bir asistanın ilerleyen zamanlarda hangi özellikleri kazanacağını maddeler halinde yazmak.
BAŞLA
1.VERİ SAKLAMA KONTROLÜ
EĞER hafızada_kullanıcı_Adı_Var_Mi()İSE
Kullanıcı_Adı=Hafızadan_Oku("Kullanıcı_Adı")
Yazdır("Tekrar hoş geldin,"+Kullanıcı_Adi)
DEĞİLSE
Kullanıcı_Adı=Kullanıcıdan_Al("Adı nedir?")
Hafizaya_Kaydet("Kullanıcı_Adi",Kullanıcı_Adi)
Yazdir("Tanıştığımız memnun oldum,"+Kullanıcı_Adi)
BİTİR
