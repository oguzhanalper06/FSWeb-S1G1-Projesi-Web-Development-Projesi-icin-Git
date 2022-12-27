## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Açık kaynak dağıtılmış sürüm kontrol sistemleridir.
2. Git ile GitHub arasında ne fark var?
Git yazılım projelerinin düzenlendiği , kontrol edilip kod eklemelerinin yapıldığı programdır. Github ise projelerin toplanıp saklandığı uzak sunucudur.
3. Neden bir branch oluşturuyoruz?
Branch, yazılım projelerini oluşturma veya yeni versiyonlarını geliştirmek adına ve bir kodlamanın heryeni versiyonunda yeni bir repository ihtiyacı kalmamasını dasağlar.
4. Pull Request'in amacı nedir?
Esas kod kaynağının sahibine kodlar üzerinde ekleme talebidir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout -b 'main'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch yerelde branch e kayıt yapar ancak eski ile yeni sürümü birleştirmez.
git pull eski ve yeni sürümü birleştirir.
merge komutu ise başka branch ile kendi branch ini birleştirme işlemidir.
7. Merge conflict nedir?
İki veya daha fazla kişinin aynı anda aynı dosyada aynı satırda değiştirirse ve git otomatik olarak merge edememe durumu.
8. Merge conflict'i nasıl çözeriz?
Hataya sebep olan kişiler kendi aralarında bu çakışmayı çözerek tekrar merge işlmeine dönülmelidir.
