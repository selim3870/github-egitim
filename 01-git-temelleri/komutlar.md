# 1. Gün - Komutlar

## `git --version`
**Ne işe yarar?** Git kurulu mu kontrol eder.
**Hata durumunda:** `'git' is not recognized` → Git'i indir ve kur.

## `git init`
**Ne işe yarar?** Klasörü Git deposuna çevirir.
**Normalde:** `Initialized empty Git repository...`

## `git status`
**Ne işe yarar?** Dosya durumlarını gösterir.
**Hata durumunda:** `fatal: not a git repository` → `git init` yap.

## `git add .`
**Ne işe yarar?** Tüm dosyaları commit'e hazırlar.

## `git commit -m "mesaj"`
**Ne işe yarar?** Değişiklikleri kalıcı kaydeder.
**Hata durumunda:** `nothing to commit` → önce `git add` yap.

## `git log --oneline`
**Ne işe yarar?** Commit geçmişini kısa gösterir.
**Çıkmak için:** `q` tuşuna bas.

## Sık sorunlar
| Hata | Çözüm |
|------|-------|
| `'git' is not recognized` | Git'i indir ve kur |
| `fatal: not a git repository` | `git init` yap |
| `nothing to commit` | Önce `git add` yap |
| `empty commit message` | `-m "mesaj"` kullan |
