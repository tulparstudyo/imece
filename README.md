# imece
Açık kaynak kodlu, Dağıtık ve Merkeziyetsiz etkileşimli tahta kilit sistemi. 

1. Secretkey ve public bilgilerin bulunduğu tek sefer üretilen ve secret key üretici tarafından saklanmayan deploy.json dosyası
   ```
   {
       "project": {
           "secret_key": "OaVMIVFltIB0f23UtM5cPHEM9HrhtpzR1UHKhcWIzQTqgQ8PzipeqO2UU75tICKV",
           "project_name": "Şehit Sedat Mekan AİHL Kilit Sistemi",
           "webservice_uri": "https://demo.com/imace/v1/",
           "webservice_user": "demo",
           "webservice_pass": "demo123",
           "organisation_name": "Şehit Sedat Mekan AİHL",
           "created_at": "2024-10-07 14:20:01"
       },
       "client": {
           "client_name": "Akıllı Tahta"
       }
    }


Bu dosya bir kez üretilir ve secret key sunucuda saklanmaz. webservis kullanıcı bilgilerinin ve şifresinin güncellenmesine izin verilir. Kullanıcı adı ve şifre basic auth metodu ile sunucuda hesap işlemlerinin yapılması amacıyla kullanılır Kullanıcı bu dosyayı, uygulamayı etkileşimli tahtalara kurmak ve kaldırmak için ihtiyaç duyar

2. deploy.json dosyası kullanarak etkileşimli tahtalara uygulamanın kuruluşu
3. Uygulama ile kullanıcı etkileşimi
4. Uygulama ile sunucu etkileşimi
5. Uygulamamnın kaldırılması
