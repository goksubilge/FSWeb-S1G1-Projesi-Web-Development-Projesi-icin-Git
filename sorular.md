Bilge Göksu


# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemidir. GitHub ise projeleri depolayabildiğimiz, üzerinde bireysel ya da ekip çalışması yapabildiğimiz ortamdır. 

3. Neden bir branch oluşturuyoruz?
Main repositorynin alternatif çalışmalarını oluşturmamızı ve kaydetmemizi sağlıyor.

4. Pull Request'in amacı nedir?
Oluşturduğumuz branch in aynı iş üzerinde çalıştığımız ekip arkadaşlarımız tarafından gözden geçirilip kendi branch ine aktarılması için talepte bulunmasına denir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git switch main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git pull; branch i çeker ve merge eder.
git fetch; branch i çeker ama merge etmez.
git merge; birleştirir.

7. Merge conflict nedir?
Ekip çalışması sırasında birden fazla kişi aynı dosda aynı satırda farklı değişiklikler yaptığında ya da bir kişi bir dosyayı düzenlediğinde ve başka birisi aynı dosyayı sildiğinde meydana gelir.

8. Merge conflict'i nasıl çözeriz?
Ekipteki çakışma yaşayan kişiler birlikte sorunu çözdükten sonra merge işlemine devam etmelidirler.
xxx