
# Java Build Tolls (Qurucu Vasitələr)
Proqramlaşdırmanın üz tutduğu yol daha rahat istifadəyə malik olmaqdır. Bunun ən bariz nümunəsi olaraq avtomatlaşdırılmış proqramları nümunə gətirmək olar. Digər adi ilə qurucu vasitələr (build tools) olan bu hazır proqram sizə bir çox cəhətdən kömək edir:
- Mənbə kodunu tərtib etmək (compile),
- Proqramı sınaqdan keçirmək,
- Quraşdırıcı (installer) yaratmaq,
- Uzaqdakı serverə (remote server) proqramı quraşdırmaq.

Qurucu vasitələr DevOps prosesinin vacib hissəsidir. Onlar vaxta qənaət etməyə, potensial problemləri vurğulamağa və tərtibatçıların işini asanlaşdırmağa kömək edir. 
Hal hazırda müxtəlif tipdə build tools proqram təminatları vardır :

-	Maven
-	Gradle
-	Apache Ant
-	Jenkins
-	TeamCity
-	Travis CI
-	CMake
-	sbt
-	MSBuild
-	Bamboo

2021-ci il `Java Developer Məhsuldarlığı Hesabatına` əsasən, Java proqramçılarının:

-	67%-i Maven, 
-	20%-i Gradle, 
-	11%-i isə Ant 
istifadə edib. Bu statistik məlumata əsasən iki ən vacib build tools haqqında davam edək.

## Maven

-	Maven, 2004-cü ildə Apache Ant-ın təkmilləşdirilməsi olaraq bazara daxil oldu. 
-	Maven açıq mənbəli Apache layihəsidir. 
-	Maven layihələri XML-də yazılmış Layihə Obyekt Modeli (POM) faylları ilə müəyyən edilir. 
-	POM.xml faylları layihənin asılılıqlarını, plaginlərini, xassələrini və konfiqurasiya məlumatlarını ehtiva edir. 

## Gradle
-	Gradle 2008-ci ildə Mavenin konsepsiyalarına əsaslanaraq, onun varisi kimi bazara çıxdı.
-	`Groovy` və `Kotlin` proqramlaşdırma dillərinə əsaslanan domen üçün xüsusi bir dil (DSL) təqdim etdi. 
-	Gradle layihə konfiqurasiyalarını elan etmək üçün Maven və Ivy repozitoriyalarını dəstəkləyir. 
-	Çox layihəli quruluşlar nəzərə alınmaqla hazırlamışdır.

### Maven və Gradle arasındakı fərqlər

Dil quruluşu baxımından Gradle-nin qurma skripti Maven-dən daha çox yönlü və güclüdür. Bunun səbəbi, Gradle proqramlaşdırma dili olan Groovy, Maven isə işarələmə dilinə (XML) əsaslanır. 
Performans baxımından Gradle keş qurmaq və artımlı kompilyasiya kimi strategiyaları istifadə etdiyi üçün daha sürətlidir.
Çeviklik və fərdiləşdirmə asanlığı baxımından Gradle-nin Groovy-əsaslı qurma skripti Maven-in XML-dən daha sürətli çeviklik təklif edir. Məsələn, siz plagin fərdiləşdirmələrini birbaşa Gradle-nin qurma skriptinə yaza bilərsiniz. Maven-in XML əsaslı konfiqurasiyası quruluşunuzu fərdiləşdirmək üçün bir neçə əlavə addım tələb edir.
Plaginlər baxımından Maven daha əvvəl yarandığı üçün daha çox plaginlərə malikdir. 
Asılılığın idarə edilməsi baxımından hər ikisi müxtəlif yanaşmalardan istifadə edir. Maven bəyannamə əmrinə əməl edir, Gradle isə asılılıq ağacına istinad edir.
Hansını seçməli?

Bu suala olan cavablara baxdıqda Gradle bir çox cəhətdən daha üstün sayılır. Bunun bir çox səbəbləri var:
-	Sürətli işləmə və quraşdırılma müddətinin azlığı
-	Gradle ilə Ant inteqrasiyasının çox yaxşı işləməsi
-	Google, Android layihələri üçün standart qurma aləti kimi Gradle qəbul edilməsi
-	Hər 6-8 həftədən bir yeni versiyanın yeni funksiyalarla bazara çıxması 

## İstinadlar

Bu yazı aşağıdaki mənbələrdən yararlanılaraq hazırlanmışdır:

- https://www.filecloud.com/blog/2019/06/top-10-build-automation-software-for-2019/
- https://www.jrebel.com/blog/java-build-tools-comparison
- https://www.educative.io/blog/java-build-tools-maven-vs-gradle
