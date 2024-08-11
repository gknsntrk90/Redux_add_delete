## STATE YÖNETİM;
- State: Uygulamadaki bileşenlerin sahip olduğu bilgi ve özelliklerdir.

- Prop Drilling: Bileşenlerin yukarıdan aşağıya veri taşımasıdır.

- Context: Uygulamadaki state'i bütün bileşenler tarafından erişilebilen ve oluşturduğumuz merkezlerden yönettiğimiz state yönetim aracıdır.

- Redux: Bileşenlerin sahip olduğu ve merkezi olarak tutulması gereken state'lerin yönetildği merkezi state yönetim aracıdır.

## NEDEN CONTEXT YERİNE REDUX?
- Kod tekrarını önler
- Performansı daha iyidir.
- Bileşenler içerisinde ki karışıklığı azaldır.
- Hata ayıklama daha kolaydır.
- Orta ve büyük ölçekli projelerde state yönetinimi daha kolay hale getirir.
 

 ## KÜTÜPHANELER
 - bootstrap
 - json-server
 - react-redux
 - redux
 - uudi

 ## Redux ile ilgili bilinmesi gerekenler;
 - 1. Store: Uygulamanın bütün bileşenleri tarafından erişilebilen ve yönetilebilen state deposu
 - 2. Reducer: Aksiyondan aldığı talimata(emir) göre store'da tutulan state'in nasıl değişeceğine karar veren fonksyondur.
 - 3. Action(Emir& Haber & Talimat): Store'da ki state'i güncellemek için reducera gönderdiğimiz nesnedir.
 --Action iki değerli bir nesne döndürür:
- type(zorunlu): Action görevini tanımlayan bir string değerdir.
- payload(opsiyonal): action verisidir. # Redux_add_delete
