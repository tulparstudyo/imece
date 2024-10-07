# imece
Dağıtık ve merkeziyetsiz etkileşimli tahta kilit sistemi. 

1. Secretkey ve public bilgilerin bulunduğu tek sefer üretilen ve üretici tarafından saklanmayan deploy.json dosyası
   ```
   {
       "project": {
           "secret_key": "OaVMIVFltIB0f23UtM5cPHEM9HrhtpzR1UHKhcWIzQTqgQ8PzipeqO2UU75tICKV",
           "project_name": "Şehit Sedat Mekan AİHL",
           "webservice_uri": "https://demo.com/imace/v1/",
           "webservice_user": "demo",
           "webservice_pass": "demo123",
           "project_name": "Şehit Sedat Mekan AİHL",
           "created_at": "2024-10-07 14:20:01"
       },
       "client": {
           "client_name": "Akıllı Tahta"
       }
    }
```

3. deploy.json dosyası kullanarak etkileşimli tahtalara uygulamanın kuruluşu
4. Uygulama ile kullanıcı etkileşimi
5. Uygulama ile sunucu etkileşimi
6. Uygulamamnın kaldırılması
