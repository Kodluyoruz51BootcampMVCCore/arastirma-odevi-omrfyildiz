# Araştırma Ödevi

**1. Solid Prensiplerini Öğren.**

**S.O.L.I.D** kısaltması Object Oriented Programlama(Nesne Tabanlı Programlama) uygulamalarında kodun daha esnek, işlevsel ve bakımının kolay olmasını sağlamak için uygulanan beş tasarım ilkesinin baş harflerinden oluşmaktadır.

- Single Responsibility(Tek Sorumluluk) Prensibi(S):
Bir class’ın(sınıfın), metodun v.s sadece bir görevi olmalıdır. Yani bir sınıfta değişiklik yaparken yalnız bir nedeniniz olmalıdır.

- Open/Closed(Açık/Kapalı) Prensibi(O):
Yazılımın entitilerinin geliştirilmeye açık, değiştirilmeye kapalı olması anlamına gelir. Kodun if/else, swtich gibi yapılarla kurmak yerine abstract ve interfaceler ile daha öz şekilde kurmak bu prensibi ifade edebilir diyebiliriz.  

- Liskov Substitution(Liskov’un Yerine Geçme) Prensibi
Bir nesneden türetilen başka bir nesnenin üst sınıfındaki tüm özellikleri içermesi anlamına gelen prensiptir.

- Interface segregation(Arayüz Ayrımı) Prensibi:
Bu prensibe göre oluşturacağımız interfaceler gereğinden fazla metot içermemelidir. 

- Dependency Inversion Prensibi
Entitiler soyutlamalara bağlı olmalıdır. Üst sınıflar alt sınıflara bağlı olmamalıdır.

**2. Microsoft Build 'den 2 etkinlik araştır.**

[The bleeding edge of modern web apps on Azure](https://mybuild.microsoft.com/sessions/6769011f-744e-4c36-84a2-49b715be0c80?source=sessions)

[Modern Web UI with Blazor WebAssembly](https://mybuild.microsoft.com/sessions/7e6c0b6e-36b9-4b9b-a409-a0960f67531f?source=sessions) 

**3. Microsoft Build 2020 yeniliklerini Araştır.**

Asp.Net Blazor WebAssembly’nin resmi olarak yayınlanması

2021 yılında Xamarin’İn evrim geçirecek hali olan .Net MAUI(Multi-platform App UI) preview olarak kullanılabiliyor.

Entity Framework Core 5 ve .Net 5 preview olarak yayınlandı. C# 9.0’ın gelişi duyuruldu. Kubernetes temelli microservisleri hedefleyen deneysel bir araç olan Project Type duyuruldu.

Azure tarafındaki gelişmeler: Özellikle makine öğrenmesi ve yapay zekaya yönelik gelişmeler, Azure Quantum ile kuantum işlem gelişmeleri, Azure Static Web Apps ile Github repositoryleri üzerinden Azure’da yayına alınabilecek full-stack web uygulamalarının mümkün olması

4. Takip Ettiğin 2 yazılımcıyı araştır.

[Bora Kaşmer](http://www.borakasmer.com/) 

[Engin Demiroğ](https://github.com/engindemirog)

**5. Devler Azure'da araştır [Eğitim-Workshop]**

  *Kubernetes ve İş Yükleri - Pamir Erdem
  
  "Bir container dünyasında network paketleri nasıl yönetiliyor?" sorusuna cevap aradığımızda karşımıza Kubernetes çıkıyor.
  Kubernetes aslında bir orkestrasyon ve networking aracı olarak düşünülebilir. Bir container orkestrasyon aracı olan Kubernetes,
  sektörde en çok tercih edilen araçtır. 
  
  Bir Kubernetes clusterındaki worker node'da neler vardır? 
  
  -Docker(Container Runtime)
  -Kubelet
  -KubeProxy
  
  Worker node'a gittiğimizde bir container runtime'a ihtiyaç var. Bunun için en sık kullanılan araç Docker.
  
  İkinci yapacağımız şey, bir container ayağa kalkarken ihtiyaç duyacağı storage, memory ve network yönetimini sağlayan komponent  Kubelet. Bu ihtiyaçların ayarlanması Kubelet'in sorumluluğunda. Containerın ayağa kalkmasından ve sağlığından sorumlu.
  
  KubeProxy ise networking işlemlerinden sorumludur.
Bir veya birden çok yapıyı barındıran yapıya Pod denir. Somut bir örnek vermek gerekirse; container balinaysa pod bir gruptan oluşan balinadır.  
  
  *DevOps Kültürü ve Azure DevOps - Mehmet Kut*
  
Geleneksel yöntemlere göre (2018 verilerine göre) 46 kez daha sık deployment yapma fırsatı veriyor. Pazara daha hızlı ürün sunarken hata yapma şansını 7 kat azaltıyor.
Ürün geliştirme süreci tarihsel olarak Non-Virtualised Hardwares-Sanal olmayan donanımlar-fiziksel sunucular ile başlamış sonra teknolojideki gelişmelerle birlikte Virtualisation(Sanallaşma) süreci ile fiziksel bir altyapı edinmenin önemi azalmaya başlamıştır. Bu süreç Open Source IaaS(Infrastructure as a Service) [Açık Kaynak Hizmet Altyapısı] gelişmeye devam edip Open Source PaaS(Platform as a Service) [Açık Kaynak Platform Olarak Hizmet] gelişti. 2013’te Containers teknolojisinin(özelde Docker) gelişimi ile birlikte yeni bir boyut kazanan bu süreç 2015’te Cloud Native teknolojisinin gelişimi ile birlikte burada karşılaşılan sorunların çözümü için DevOps kültürü doğmaya başladı. DevOps belirttiğmiz gibi bir uygulama değil, bir kültürdür. 

*Azure DevOps ile Uygulama Derleme ve Dağıtma – Mehmet Kut*

-Azure DevOps

-Azure Pipelines
  Build
  Release

-Agents

DevOps’un Zorlukları: Different Approaches(Farklı Yaklaşım Tutumları), Save Cloud Endpoint

DevOps Artıları:
-	Development takımlarının birbirinden bağımsız çalışabilmesi
-	Development takımlarının birbirinden kontrol edilebilmesi
-	Development takımlarının birbirinden çalışma süreçlerinden hoşlanırlar.

DevOps Eksileri:
-	Farklı takımların farklı yaklaşımlarının olabilmesi
-	Farklı takımların kontrolünün zor olabilmesi
-	Operasyonel zorluklar
-	Güvenlik zorlukları

Azure DevOps beş ana üründen oluşur:
-	Azure Boards: Planlama ve İzleme
-	Azure Pipelines: Build, Test, Deploy
-	Azure Repos: Daha iyi kodlama için işbirlği
-	Azure TestPlans: Test and Ship
-	Azure Artifacts: Create, Host and Share, Packages(npm, Nugets)

**6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)

[From games to apps to APIs and more, prototype ANY idea of your choosing](https://global-dev-challenge.devpost.com/?ref_content=default&ref_feature=challenge&ref_medium=discover)

[Developer Week Global](https://developerweek-global-2020.devpost.com/?ref_content=default&ref_feature=challenge&ref_medium=discover)
