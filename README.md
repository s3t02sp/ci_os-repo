# CI_OS Package Repository

Все пакеты и БД хранятся в GitHub Release.
pacman скачивает пакеты напрямую по имени файла.

```ini
[ci_os]
SigLevel = Optional TrustAll
Server = https://github.com/s3t02sp/ci_os-repo/releases/download/packages-latest
```

## Файлы в Release

| Файл | Описание |
|------|----------|
| ci_os.db | БД (копия ci_os.db.tar.zst) |
| ci_os.db.tar.zst | БД архив |
| ci_os.files | Files (копия ci_os.files.tar.zst) |
| ci_os.files.tar.zst | Files архив |
| ci_os-calamares-*.pkg.tar.zst | Установщик Calamares |
| helium-browser-*.pkg.tar.zst | Браузер Helium |
| ckbcomp-*.pkg.tar.zst | ckbcomp |
| mkinitcpio-openswap-*.pkg.tar.zst | mkinitcpio-openswap |

Обновлено: 2026-07-07
