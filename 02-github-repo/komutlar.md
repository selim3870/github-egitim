# 2. Gün - Komutlar

## `git remote add origin URL`
**Ne işe yarar?** Yerel repoyu GitHub'daki uzak repoya bağlar.
**Hata durumunda:** `fatal: remote origin already exists` → `git remote set-url origin YENI_URL`

## `git push -u origin main`
**Ne işe yarar?** Kodları ilk kez GitHub'a gönderir.
**Hata durumunda:** `! [rejected] main -> main` → `git pull origin main --allow-unrelated-histories` sonra tekrar dene.

## `git push`
**Ne işe yarar?** Kodları GitHub'a gönderir (ilk `-u` dan sonra).

## `git pull origin main`
**Ne işe yarar?** GitHub'daki güncellemeleri yerel repoya çeker.
**Hata durumunda:** `fatal: refusing to merge unrelated histories` → `git pull origin main --allow-unrelated-histories`

## `git clone URL`
**Ne işe yarar?** GitHub'daki bir repoyu bilgisayarınıza kopyalar.

## Sık sorunlar
| Hata | Çözüm |
|------|-------|
| `remote origin already exists` | `git remote set-url origin YENI_URL` |
| `rejected main -> main` | `git pull origin main --allow-unrelated-histories` sonra `git push` |
| `authentication failed` | GitHub'da Personal Access Token oluştur, şifre yerine onu kullan |
| `unrelated histories` | `git pull origin main --allow-unrelated-histories` |
