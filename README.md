<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║              P R O J E C T   D I A R Y   V 3                     ║
║                                                                  ║
║         encrypted video diary  ·  local vault  ·  HUD            ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

# Project Diary V3

### Зашифрованный видеодневник для Windows

`позывной + пароль` &nbsp;·&nbsp; `локальный сейф` &nbsp;·&nbsp; `без облака`

<br>

### 🌐 Официальный сайт

# [projectdiary.ru](https://projectdiary.ru/index.html)

<sub>всё о проекте · новости · скачивание</sub>

<br>

[![Website](https://img.shields.io/badge/OPEN%20SITE-projectdiary.ru-00B4FF?style=for-the-badge&labelColor=00B4FF&color=0A0E14&logo=googlechrome&logoColor=white)](https://projectdiary.ru/index.html)
&nbsp;
[![Release](https://img.shields.io/badge/DOWNLOAD-GitHub%20Releases-2AA84A?style=for-the-badge&labelColor=0A0E14&logo=github&logoColor=white)](../../releases)

<br>

<img src="https://img.shields.io/badge/PLATFORM-Windows%2010%20%2F%2011%20x64-00B4FF?style=flat-square&labelColor=0A0E14" alt="Windows">
<img src="https://img.shields.io/badge/VAULT-AES--256--GCM-2AA84A?style=flat-square&labelColor=0A0E14" alt="AES">
<img src="https://img.shields.io/badge/MODE-OFFLINE%20FIRST-C8B028?style=flat-square&labelColor=0A0E14" alt="Offline">
<img src="https://img.shields.io/badge/BY-Steford's%20Tempus-1E2B32?style=flat-square&labelColor=0A0E14" alt="Tempus">
<img src="https://img.shields.io/badge/©-2026-071015?style=flat-square&labelColor=0A0E14" alt="2026">

```
◆━━━━━━  AUTH GATE  ·  LOCAL NODE  ·  SECURE ENCLAVE  ━━━━━━◆
```

</div>

---

<div align="center">

## ▌ Идея

**Не всё стоит писать. Иногда нужно сказать вслух — и оставить это себе.**

Project Diary — тихий ритуал на камеру: ты говоришь, день сохраняется, чужие глаза сюда не ходят.

</div>

---

<div align="center">

## ▌ Что внутри

</div>

<table>
<tr>
<td width="50%" valign="top">

### ◆ Записи
Включаешь камеру и ведёшь дневник как разговор с собой. Дни складываются в календарь — легко вернуться к любому моменту.

</td>
<td width="50%" valign="top">

### ◆ Проекты
Можно вести отдельные проекты — личное, работа, учёба — и не смешивать всё в одну кучу.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ◆ Эмоции
Мягкая сводка настроения после записи — не оценка личности, а зеркало дня.

</td>
<td width="50%" valign="top">

### ◆ Транскрипт
Сказанное становится текстом: перечитывай, ищи фразы, цепляйся за мысли.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ◆ Голосовые метки
Закладки и команды голосом по ходу записи — руки свободны, момент не теряется.

</td>
<td width="50%" valign="top">

### ◆ Экспорт
Нужна копия или файл «на сторону» — готовое видео можно выгрузить.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ◆ Форматы
Горизонталь под монитор или вертикаль под телефон — как удобнее снимать.

</td>
<td width="50%" valign="top">

### ◆ Защита
Доступ по позывному и паролю. Без ключа архив закрыт.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ◆ Дизайн
Sci-fi HUD: тёмный, чёткий, без шума. Фокус на записи, не на кнопках.

</td>
</tr>
</table>

---

<div align="center">

## ▌ Сценарий

```text
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐
│   AUTH   │───▶│ ARCHIVE  │───▶│  RECORD  │───▶│  PLAYER  │
│ callsign │    │ calendar │    │   log    │    │  replay  │
└──────────┘    └──────────┘    └──────────┘    └──────────┘
```

**1.** Разблокируй сейф &nbsp;→&nbsp;
**2.** Выбери день &nbsp;→&nbsp;
**3.** Запиши &nbsp;→&nbsp;
**4.** Вернись к себе

</div>

---

<div align="center">

## ▌ Установка

</div>

```text
 ①  скачай ProjectDiarySetup.exe   ←  GitHub Releases
 ②  установи и задай позывной + пароль
 ③  позывной — часть ключа, не просто ник
```

> **Не теряй позывной и пароль.** Без них архив не восстановить.

---

<div align="center">

## ▌ Стек

<img src="https://skillicons.dev/icons?i=dotnet,windows,cpp,py&theme=dark" alt="stack" />

<br><br>

<img src="https://img.shields.io/badge/WPF-.NET%208-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="WPF">
<img src="https://img.shields.io/badge/MediaCapture-WinRT-0078D6?style=flat-square&logo=windows&logoColor=white" alt="MC">
<img src="https://img.shields.io/badge/WebView2-Edge-0078D6?style=flat-square&logo=microsoftedge&logoColor=white" alt="WV2">
<img src="https://img.shields.io/badge/ffmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="ffmpeg">
<img src="https://img.shields.io/badge/Vosk-00B4FF?style=flat-square" alt="Vosk">
<img src="https://img.shields.io/badge/Whisper-C8B028?style=flat-square" alt="Whisper">
<img src="https://img.shields.io/badge/ONNX-FF6F00?style=flat-square&logo=onnx&logoColor=white" alt="ONNX">

</div>

---

<div align="center">

## ▌ Лицензия

```
© 2026  ·  Steford's Tempus  ·  Project Diary V3
```

Копирование и коммерческое использование — только с разрешения.  
[LICENSE.txt](LICENSE.txt) · [LICENSE-THIRD-PARTY.txt](LICENSE-THIRD-PARTY.txt)

<br>

```
◆━━━━━━  AUTH GATE  ·  LOCAL VAULT  ·  PROJECT DIARY  ━━━━━━◆
```

### [▶  projectdiary.ru  ◀](https://projectdiary.ru/index.html)

</div>
