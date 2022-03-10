index.html 

--- navbar ---

class= "navbar navbar-expand-md bg-dark navbar-dark"
navbar-expand-md(lg/sm) responsive olması için gerekli bir komut. daha sonra bg-dark ile navbarın arkaplan rengini değiştiriyoruz. navbar-dark ile navbarın rengini değiştiriyoruz. navbar-dark sayesinde üstüne koyduğumuz yazılar otomatik olarak navbar'ın rengine uyum sağlayacak.

<a class="navbar-brand"> ile brandimizi oluşturacağız. brandimizi oluşturmak için a tagının içine yazdığımız yazıyı yazıyoruz. brandimiz normalde mavi olacaktı fakat yukarıdaki navbar-dark sayesinde yazımız navbarın rengine uyum sağladı ve beyaz oldu.

şimdi sağ taraftaki linklerimizi oluşturacağız. <ul class="navbar-nav"> içerisine <li class="nav-item"> içerisine <a class="nav-link">'e de linklerimizin ismini yazıyoruz. <li>'nin clasına "text-uppercase" yazarak hepsini büyük harfe çevirdik. ayrıca hangi sayfada olduğumuzu göstersin diye tekrar <li> içerisine "border-bottom border-warning border-3" yazarak home linkinin altına sarı bir çizgi ekliyoruz. 

navbarımızı hizalamak için brand ve linkleri bir div içerisine aldık ve classını "container" olarak verdik.

linklerin üstüne toggler butonu ekleyeceğiz. <button class="navbar-toogler"> içerisine <span class="navbar-toggler-icon"></span> yazıyoruz. böylece toggler butonu oluşturduk. şimdi toggler butonuna tıklayınca navbarımızın açılma ve kapanmasını sağlamak için yeni bir div oluşturup <ul> 'yi ve içerisindekileri bu dive yerleştireceğiz.

oluşturduğumuz div'e class="collapse navbar-collapse" verdik. ve bir id verdik. böylece id ile az önce oluşturduğumuz butonu birbirine bağlayabileceğiz. 
butonumuza data-bs-target="#id" yazarak bu bağlantıyı sağladık. yine buttonumuza data-bs-toggle="collapse" ile toggle durumunda ne işlem yapacağını belirttik.

--- Carousel ---