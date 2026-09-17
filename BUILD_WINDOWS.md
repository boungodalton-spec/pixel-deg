# Compilation Windows

Le module `desktop` est activé dans `settings.gradle`.

Le workflow `.github/workflows/build-windows.yml` compile la version PC sur un runner Windows avec Java 17, puis crée une image Windows et tente de générer un installateur EXE.
