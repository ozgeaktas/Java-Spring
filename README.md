# Java-Spring

JAVA dilinde, sıkı bağlılık (tight coupling) ve yumuşak bağlılık (loose coupling) kavramları sınıflar arasındaki bağımlılık düzeyini ifade eder. Sıkı bağlılık, bir sınıfın bir başka sınıfa olan bağımlılığının yüksek olduğu anlamına gelir. Bu durumda, bir sınıfın işlevselliği, başka bir sınıfa olan bağımlılığını değiştirerek değiştirilebilir veya etkileyebilir. Yumuşak bağlılık ise, bir sınıfın bir başka sınıfa olan bağımlılığının düşük olduğu anlamına gelir. Bu durumda, bir sınıfın işlevselliği, başka bir sınıfa olan bağımlılığını değiştirse bile etkilenmez. Yumuşak bağlılık, sınıflar arasındaki bağımlılıkların düşük olduğu anlamına gelir ve bu, sınıfların daha esnek ve daha test edilebilir hale gelmesini sağlar.
Gerçek hayattan bir örnek verecek olursam: Laptop çevreye loose coupling tir çünkü hareket ettirmemiz daha kolaydır fakat masaüstü bilgisayar çevreye tight coupling tir bir yerden bir yere taşımak laptopa göre daha zordur.
<br>
Uygulamada ise;

![Ekran Görüntüsü (739)](https://user-images.githubusercontent.com/54955167/207057365-3973f99b-01dd-4c32-b221-8be31865ac6e.png)

GameRunner class'ı Mario,SuperContra ve Pacman oyunlara göre kodu değişir yani bu oyunlara tight coupling'tir. Fakat ikinci durumda GamingConsole isimli interface kullanılarak GameRunner class'ı sadece bu interface'e bağımlı hale gelmiştir buna da loose coupling denir.
