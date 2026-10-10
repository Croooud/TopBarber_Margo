Видео для ленты «Процесс работы» (вертикальные 9:16, H.264, без звука, файл ≈ 0,3–1,8 МБ):
video1.mp4 … video8.mp4  — ролики (водяные знаки удалены, заставки-логотипы в конце обрезаны)
poster1.jpg … poster8.jpg — кадры-заставки

Как заменить ролик: положите новый файл с тем же именем. Как добавить: скопируйте <article class="reel"> в index.html.
Сжатие нового видео:
ffmpeg -i исходник.mp4 -vf "scale=720:-2" -c:v libx264 -crf 27 -preset slow -pix_fmt yuv420p -an -movflags +faststart video9.mp4
