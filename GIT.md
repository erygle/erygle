## İlk Yapılandırma

Git'i yükledikten sonra, adınızı ve e-posta adresinizi yapılandırmanız gerekir:

```sh
git config --global user.name "Adınız Soyadınız"
```
```sh
git config --global user.email "email@example.com"
```

## Yeni Bir Git Deposu Oluşturma
Bir proje dizini oluşturun ve bu dizinde yeni bir Git deposu başlatın:
```sh
mkdir deneme
```
```sh
cd deneme
```
```sh
git init
```

## Repoyu Kopyalamak
```sh
git clone https://github.com/erygle/
```

## Dosyayı İzlemek
Belirtilen dosyayı izlemek için
```sh
git add file
```
Tüm dosyaları izlemek için
```sh
git add .
```
```sh
git commit -m ""
```

## Repoyu Yönetmek
```sh
git branch -M main
```
```sh
git remote add origin https://github.com/erygle/
```
```sh
git pull origin main
```

```sh
git push origin main
```

## Durum Kontrol
```sh
git status
```

## Commit Geçmişi
```sh
git log
```
