# GAGARIN NMS

**A base editor for No Man's Sky** — build a base in the app, the game opens it as
its own. Free.
**Редактор баз для No Man's Sky** — собираешь базу в программе, а игра открывает
её как свою. Бесплатно.

Download / Скачать: [**Releases**](../../releases)

[English](#english) · [Русский](#по-русски)

![A temple built in the app](screens/01_hram_snaruzhi.jpg)

---

## Screenshots · Как это выглядит

Everything below was built and captured inside the app.
Всё, что ниже, построено и снято прямо в программе.

| | |
|---|---|
| ![Inside the temple](screens/02_hram_vnutri.jpg) | ![Corvette in space](screens/03_korvet_kosmos.jpg) |
| Inside the same build · Внутри той же постройки | Corvette against the Milky Way · Корвет на фоне Млечного Пути |
| ![Corvette interior](screens/04_korvet_vnutri.jpg) | ![Station interior](screens/05_stanciya_vnutri.jpg) |
| Corvette interior · Интерьер корвета | Station interior · Интерьер станции |
| ![Platform](screens/06_platforma.jpg) | ![Base at night](screens/07_baza_nochyu.jpg) |
| Living platform · Жилая платформа | The same base at night · Та же база ночью |
| ![Parts panel](screens/08_panel_detaley.jpg) | ![Save Manager](screens/09_save_manager.jpg) |
| Parts panel: 1549 in-game parts · Панель деталей | Bases read from the game save · Базы из сохранения игры |

---

## English

### What it does

- **Parts panel** — 1549 in-game parts with their real models, icons and names in
  17 languages; search, groups, favourites.
- **Building like in the game** — snapping, move/rotate/scale gizmo, free mode,
  mirror, placement along a curve, prefabs (your own multi-part blocks).
- **Painting** — the game's own colours and finishes, plus a colour picker that
  copies paint from a part already placed.
- **Saves** — reads bases straight from your No Man's Sky save and writes them back.
- **View** — panoramic backgrounds, ground coverings (snow, grass, sand), time of
  day, light and image settings.
- **Base tabs** and session restore: the app remembers what you were building.

### Install

1. Download **all archive parts** from Releases (`.zip.001`, `.zip.002`).
2. Put them in one folder and extract the **first** one (`.zip.001`) — 7-Zip or
   WinRAR will pick up the rest by themselves.
3. Run `GAGARIN_NMS\GAGARIN NMS.exe`.

No installer, nothing is written to the registry. To uninstall, delete the folder.

**Requirements:** Windows 10/11 64-bit, a DirectX 12 capable GPU, about 7 GB of
disk space (3 GB archive + 3.1 GB unpacked).

### Windows warns on first launch

"Windows protected your PC" appears for any app without a paid developer
signature. Click **More info → Run anyway**. To be sure you got exactly what was
published, check the SHA-256 below.

### About game saves — important

The app can write a finished base straight into your No Man's Sky save. Built-in
safeguards:

- writing is **blocked while the game is running** (otherwise the game overwrites
  the file with its own copy);
- a **dated backup of the save** is made before every write, so you can always
  roll back;
- after writing, the file is read back and verified.

Even so: **make your own copy of the save folder before the first experiments.**
Those are your hours of play.

Game saves live here:

```
%APPDATA%\HelloGames\NMS
```

The app's own settings and tabs:

```
%LOCALAPPDATA%\NMS_BuilderApp\Saved
```

### Verify the download

Each part in the release has a `.sha256` file next to it. Check yours:

```powershell
Get-FileHash 'GAGARIN_NMS_v1.0.0.zip.001' -Algorithm SHA256
```

The string must match the one in the release notes.

### If something breaks

Tell me what you did, what you expected and what happened instead. Useful details:
game version, GPU model, and the base file it stumbled on. Contact links and the
author's support page are inside the app, in the bottom row of the main menu.

---

## По-русски

### Что умеет

- **Панель деталей** — 1549 деталей игры с их настоящими моделями, иконками и
  названиями на 17 языках; поиск, группы, избранное.
- **Стройка как в игре** — прилипание деталей друг к другу (снап), гизмо
  перемещения/поворота/масштаба, свободный режим, зеркало, расстановка по кривой,
  префабы (свои заготовки из нескольких деталей).
- **Покраска** — цвета и отделки игры, пипетка цвета с уже поставленной детали.
- **Работа с сейвом** — чтение баз прямо из сохранения игры и запись обратно.
- **Вид** — панорамные фоны, покрытия земли (снег, трава, песок), время суток,
  настройки света и картинки.
- **Вкладки баз** и восстановление сессии: программа помнит, что ты строил.

### Как запустить

1. Скачать **все части архива** из раздела Releases (`.zip.001`, `.zip.002`).
2. Положить их в одну папку и распаковать **первую** (`.zip.001`) — 7-Zip или
   WinRAR подхватят остальные сами.
3. Запустить `GAGARIN_NMS\GAGARIN NMS.exe`.

Установка не нужна, реестр программа не трогает. Чтобы удалить — просто удали
папку.

**Требования:** Windows 10/11 64-бит, видеокарта с поддержкой DirectX 12,
около 7 ГБ на диске (3 ГБ архив + 3.1 ГБ распакованное).

### Windows ругается при запуске

«Система Windows защитила ваш компьютер» — так бывает у любой программы без
платной подписи разработчика. Нажми **«Подробнее» → «Выполнить в любом случае»**.
Хочешь убедиться, что скачал именно то, что выложено — сверь контрольную сумму.

### Про сохранения игры — важное

Программа умеет писать построенную базу прямо в сохранение No Man's Sky.
Встроенные предохранители:

- запись **блокируется, пока игра запущена** (иначе игра затрёт файл своим);
- перед записью делается **копия сохранения** с датой, откатиться можно всегда;
- после записи файл перечитывается и проверяется.

И всё же: **перед первыми опытами сделай копию папки сохранений сам.** Это
твои часы игры, лишняя копия ещё никому не мешала.

Сохранения игры лежат здесь:

```
%APPDATA%\HelloGames\NMS
```

Настройки и вкладки самой программы — здесь:

```
%LOCALAPPDATA%\NMS_BuilderApp\Saved
```

### Проверить, что архив не подменили

В релизе рядом с каждой частью лежит файл `.sha256`. Сверить у себя:

```powershell
Get-FileHash 'GAGARIN_NMS_v1.0.0.zip.001' -Algorithm SHA256
```

Полученная строка должна совпасть с той, что в описании релиза.

### Если что-то не так

Напиши мне — что делал, что ожидал, что получилось. Пригодятся: версия игры,
модель видеокарты и файл базы, на которой споткнулось. Ссылки на связь и на
страницу поддержки автора есть в самой программе, в нижнем ряду главного меню.

---

Free, made by one person. Part models, icons and names belong to Hello Games —
the app only shows what already sits in your copy of the game.

Программа бесплатная и делается одним человеком. Модели, иконки и названия
деталей принадлежат Hello Games — программа лишь показывает то, что уже лежит
у тебя в игре.
