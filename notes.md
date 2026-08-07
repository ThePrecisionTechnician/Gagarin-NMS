First build for friends. No installer: unpack and run.
Первая сборка для друзей. Установка не нужна: распаковал и запустил.

## Install

1. Download **both parts**: `GAGARIN_NMS_v1.0.0.zip.001` and
   `GAGARIN_NMS_v1.0.0.zip.002` (the archive is split in half because GitHub
   does not accept files over 2 GB).
2. Put them in one folder and extract the **first** one (`.zip.001`) — 7-Zip or
   WinRAR will pick up the second by themselves.
3. Run `GAGARIN_NMS\GAGARIN NMS.exe`.

Windows will show "Windows protected your PC" — that happens with any app without
a paid developer signature. Click **More info → Run anyway**.

**Requirements:** Windows 10/11 64-bit, a DirectX 12 capable GPU, ~7 GB of disk space.

**About game saves.** The app can write a finished base straight into your No Man's
Sky save. It blocks writing while the game is running and makes a dated backup of
the save before every write. Even so — **make your own copy of
`%APPDATA%\HelloGames\NMS` before experimenting.**

## SHA-256

```
f34cbd0517ce60435e1afb021516a2d867fe6ff77db3f57758c85f05ab69d028  GAGARIN_NMS_v1.0.0.zip.001
01dfb77a005f31af8ddb25c05979fa29d84dd81c5273f2d4eaa46135d84e3a0f  GAGARIN_NMS_v1.0.0.zip.002
```

Check yours / Проверить у себя:

```powershell
Get-FileHash 'GAGARIN_NMS_v1.0.0.zip.001' -Algorithm SHA256
```

## What's inside

1549 in-game parts with their real models and icons, snapping, move/rotate/scale
gizmo, mirror, placement along a curve, prefabs, the game's own colours and
finishes, reading and writing bases in the game save, panoramic backgrounds and
ground coverings, base tabs and session restore, interface in 17 languages.

---

## Как поставить

1. Скачать **обе части**: `GAGARIN_NMS_v1.0.0.zip.001` и `GAGARIN_NMS_v1.0.0.zip.002`
   (архив разрезан пополам, потому что GitHub не принимает файлы больше 2 ГБ).
2. Положить их в одну папку и распаковать **первую** (`.zip.001`) — 7-Zip или
   WinRAR подхватят вторую сами.
3. Запустить `GAGARIN_NMS\GAGARIN NMS.exe`.

Windows покажет «Система Windows защитила ваш компьютер» — так бывает у любой
программы без платной подписи. «Подробнее» → «Выполнить в любом случае».

**Нужно:** Windows 10/11 64-бит, видеокарта с DirectX 12, ~7 ГБ на диске.

**Про сохранения игры.** Программа умеет писать построенную базу прямо в
сохранение No Man's Sky. Она блокирует запись, пока игра запущена, и делает копию
сохранения с датой перед каждой записью. И всё же — **сделай копию папки
`%APPDATA%\HelloGames\NMS` сам**, прежде чем экспериментировать.

## Что в сборке

1549 деталей игры с их настоящими моделями и иконками, прилипание деталей
(снап), гизмо перемещения/поворота/масштаба, зеркало, расстановка по кривой,
префабы, покраска цветами и отделками игры, чтение и запись баз в сохранение,
панорамные фоны и покрытия земли, вкладки баз и восстановление сессии,
интерфейс на 17 языках.

Нашли беду — напишите, что делали и что получилось. Ссылки на связь есть в самой
программе, в нижнем ряду главного меню.
