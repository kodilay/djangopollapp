# djangopollapp

Django Polls uygulaması, Django MVC (Model-View-Controller) tasarım modeline dayanır. Uygulamanın modeli, Question ve Choice adında iki sınıftan oluşur. Question sınıfı, anketin sorusunu ve yayınlanma tarihini içerirken, Choice sınıfı, anketin seçeneklerini ve her seçeneğe verilen oy sayısını içerir. Bu modeller, Django'nun ORM (Object-Relational Mapping) özelliği sayesinde veritabanında depolanır.

Django Polls uygulamasının yönetici arayüzü, Django'nun otomatik olarak sağladığı ve kullanıcılara anketleri ve seçenekleri oluşturma, düzenleme ve silme imkanı veren bir özelliktir. Bu yönetici arayüzü, QuestionAdmin sınıfı ve ChoiceInline sınıfı kullanılarak oluşturulur.

Uygulamanın görünümü, kullanıcılara anketleri görüntülemeleri, anketlere oy vermeleri ve sonuçları görüntülemeleri için bir dizi sayfadan oluşur. Görünüm, Django'nun templateleri kullanılarak oluşturulur ve kullanıcılara anketleri ve seçenekleri gösterir.

Django Polls uygulaması, Django ile web uygulamaları oluşturmanın temellerini öğrenmek için harika bir örnek uygulamadır. Bu uygulama, web geliştirme ve Django hakkında yeni olanlar için idealdir ve aynı zamanda daha deneyimli geliştiriciler için de yararlı bir kaynak olabilir.
