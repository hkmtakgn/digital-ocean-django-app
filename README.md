\# Digital Ocean App Platform - Django App

Tamam, o zaman önce \*\*GitHub’da repo oluşturmamız gerekiyor\*\*. Ardından CMD üzerinden push edebiliriz. İşte adım adım yapılacaklar:



---



\# 1️⃣ GitHub’da yeni repo oluştur



1\. GitHub’a gir: \[https://github.com/new](https://github.com/new)

2\. Repository name: `digital-ocean-django-app`

3\. Public veya Private seç (tercihine göre)

4\. “Add README” işaretlemene gerek yok, çünkü CMD’den ekleyeceğiz

5\. \*\*Create repository\*\* butonuna bas



Repo URL’i şöyle olacak:



```

https://github.com/hkmtakgn/digital-ocean-django-app.git

```



---



\# 2️⃣ CMD’de remote URL’yi ayarla



Mevcut remote varsa değiştireceğiz:



```sh

git remote set-url origin https://github.com/hkmtakgn/digital-ocean-django-app.git

```



Kontrol:



```sh

git remote -v

```



---



\# 3️⃣ README veya diğer dosyaları commit et



Önce değişiklikleri ekle:



```sh

git add README.md

```



Commit oluştur:



```sh

git commit -m "Initial commit"

```



---



\# 4️⃣ Main branch’i hazırla (zaten varsa atla)



```sh

git branch -M main

```



---



\# 5️⃣ Push et



```sh

git push -u origin main

```



✅ Artık repo GitHub’da oluşacak ve tüm dosyalar yüklenecek.





