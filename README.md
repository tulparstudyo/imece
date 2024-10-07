# imece
Dağıtık ve merkeziyetsiz etkileşimli tahta kilit sistemi. 

1. Secretkey ve public bilgilerin bulunduğu tek sefer üretilen ve üretici tarafından saklanmayan deploy.json dosyası
    ``
{
    "server": {
        "secret_key": "OaVMIVFltIB0f23UtM5cPHEM9HrhtpzR1UHKhcWIzQTqgQ8PzipeqO2UU75tICKV",
        "webservice_uri": "https://demo.com/imace/v1/",
        "webservice_ip": "0.0.0.0",
    }
    "project": {
        "secret_key": "OaVMIVFltIB0f23UtM5cPHEM9HrhtpzR1UHKhcWIzQTqgQ8PzipeqO2UU75tICKV",
        "project_name": "Şehit Sedat Mekan AİHL",
        "webservice_uri": "https://demo.com/imace/v1/",
        "project_name": "Şehit Sedat Mekan AİHL",
        "client_name": "Akıllı Tahta"
    }
}
``
3. deploy.json dosyası kullanarak etkileşimli tahtalara uygulamanın kuruluşu
4. Uygulama ile kullanıcı etkileşimi
5. Uygulama ile sunucu etkileşimi
6. Uygulamamnın kaldırılması
