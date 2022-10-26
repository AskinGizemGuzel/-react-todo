Günlük , haftalık planlar yapıp bunları takip etme aşamasında kimi sadece kağıt ve kalem kullanırken kimi de sıklıkla tercih edilen todo list uygulamaları kullanır.
Bu proje içerisinde react ile bir todo uygulaması yapılmıştır.Projeyi indirdikten sonra projenin bulunduğu klasörde "npm install" komutu ile gerekli paketlerin 
yüklenmesinin ardından "npm run start" komutu ile uygulama servisi başlatılabilir.
Bu uygulama ile yeni planlar oluşturabilir , tamamlananların üstünü çizebilir , iptal olan planları silebilir ya da 
yapılan bir plan üzerinde düzenlemeler yapabilirsiniz.

Kısaca , başlangıçta bir todoApp klasörü oluşturulur ve bu klasörün içerisine bir alt klasör daha eklenerek react-todo-app-v1-yt ismi verilir ve ardından 
terminalden (Command Prompt) bu klasör içerisine npx create-react-app komutu ile bir react create edilir.Kurulum tamamlandıktan sonra terminal üzerinden 
react-todo-app-v1-yt klasörü içerisine girilerek npm start komutu ile proje localhost:3000 servisi ile açılır.src dosyası altındaki işimize yaramayacak dosyalar silinip 
yine src altında components klasörü oluşturularak Todo.js , TodoForm.js , TodoList.js dosyaları eklenir.Proje içerisinde detayları paylaşılan konfigürasyonlar yapılır.
Sonrasında projeye görsellik katabilmek için App.css içerisinde uygulamaya stil oluşturulur.


Not: Proje içerisinde; useState,useEffect,useRef state hook'ları kullanıldı.UseState() fonksiyonu ile fonksiyon component'i içerisinde çağırıp içerisine istediğimiz 
state değişkenlerini atanabilir.Butona tıklanıp tekrar render edilme esnasında React bu state'i korur.UseEffect() ile  React, DOM ile ilgili herhangi bir işlem 
tamamlandığında çağırır. React, varsayılan olarak ilk render da dahil olmak üzere her render işleminden sonra effect fonksiyonunu çalıştırır.UseRef ise, dom elemanına
ya da react render metodu içerisinde oluşturulan ögelere erişmeye imkan tanır.
