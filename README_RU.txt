RUSSIAN RIDER 2 — ALPHA 4.5 / ANDROID

Это ИСХОДНЫЙ ПРОЕКТ для сборки APK, а не готовый APK.
Оригинальный HTML из вашего файла сохранён без изменений: app/src/main/assets/index.html.
Главное меню и карта не заменялись.

КАК СОБРАТЬ НА КОМПЬЮТЕРЕ:
1. Установите Android Studio с Android SDK 35 и JDK 17.
2. Откройте папку проекта в Android Studio (File > Open).
3. Если Studio просит Gradle, выберите установленный Gradle 8.9 (или сгенерируйте Gradle Wrapper).
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Получите app/build/outputs/apk/debug/app-debug.apk и установите его на Android.

ВАРИАНТ ЧЕРЕЗ GITHUB ACTIONS (без Android Studio):
1. Создайте репозиторий GitHub и загрузите СОДЕРЖИМОЕ папки проекта в корень репозитория, включая .github.
2. Откройте Actions > Build Russian Rider 2 APK > Run workflow.
3. После успешной сборки скачайте артефакт RussianRider2-Alpha45-APK и извлеките app-debug.apk.
4. Перенесите APK на Android и установите, разрешив установку из выбранного источника.

ВАЖНО: Игра использует Three.js с внешнего CDN. Для первого запуска нужен интернет.
Android WebView должен поддерживать WebGL; производительность зависит от устройства.
Сборка APK и тест на реальном Android в этой среде не проводились.
