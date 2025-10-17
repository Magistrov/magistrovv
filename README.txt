MAGISTROV — Single-file Site (no proxy) — FIXED
==================================================

Что внутри
- index.html — автономный сайт (тёмная тема, параллакс, preloader с логотипом M, музыка по клику с fade-in, звуки клика и наведения, 3D-эффект видео, аватар поверх баннера, видео YouTube без прокси).

Публикация на GitHub Pages (кратко)
1) Создай репозиторий: magistrovv
2) Залей файл index.html в корень репозитория
3) Settings → Pages → Deploy from a branch; Branch: main /(root)
4) Открой ссылку: https://magistrov.github.io/magistrovv/

Заменить музыку
- Найди тег <audio id="bgm"> и замени URL в <source src="...">.

Обновить YouTube API ключ
- Найди константу K_PARTS и вставь свой ключ (по частям или целиком).

Обновить соцсети/текст
- Раздел "Мои соцсети" и заголовок <h1 class="hero"> находятся в index.html — измени по желанию.

💡 Обновить сайт без потери настроек
- Просто замени index.html в репозитории magistrovv (Pages всё перезальёт автоматически).
