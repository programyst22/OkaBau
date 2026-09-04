# OKA Bau — как менять фото и видео через GitHub

Просто заменяйте файл в папке `assets` новым файлом с тем же именем и делайте Commit changes.

- `logo.png` — логотип
- `director.jpg` — фото Katherina Kling
- `hero.mp4` — главное Hero-видео
- `feature-1.jpg` ... `feature-5.jpg` — фото блока Kompetenzen
- `project-1.mp4` ... `project-3.mp4` — видео проектов
- `project-1.jpg` ... `project-3.jpg` — обложки видео проектов

Важно: имя и расширение файла должны оставаться такими же.
После Commit changes Vercel автоматически создаст новый deployment, если репозиторий подключен к Vercel.


## v16 notes
- Hero scroll zoom removed.
- Director section uses the approved full-body JPG from the Higgsfield CDN so the complete figure can be shown without cropping.
- Legal pages added: `impressum.html` and `datenschutz.html`.
- If you later want the director image fully local in GitHub, download the approved JPG and replace the image source with `assets/director.jpg`.
