# Fix small khmer font for Windows 10/11

## Currently works for apps that are not Windows Native for example Telegram

## What you need **INSTALL FOR ALL USERS**
Use the fonts from the static folder for best reults!
I like Google Noto font series so you can use these:
- Noto Sans Khmer https://fonts.google.com/noto/specimen/Noto+Sans+Khmer
- Noto Serif Khmer https://fonts.google.com/noto/specimen/Noto+Serif+Khmer

### Using other fonts
You can use any font but you will need to modify the .reg file. Just change the file to whatever font you installed. You can get the right file name in Control Panel > Font > Font Properties
![image](https://github.com/henrychea/windows-change-khmer-font/assets/40254517/1ab98045-427f-4d6d-91ec-dbbc3ce9bc54)

![image](https://github.com/henrychea/windows-change-khmer-font/assets/40254517/c560fcd9-b1f8-4d7b-a108-1b7301640674)

So in this example change this in the .reg file 
`"DaunPenh (TrueType)"="NotoSansKhmer-Regular.ttf"` to `"DaunPenh (TrueType)"="calibri.ttf"`

## Why do this?
As you may have expereinced the default Khmer font installed by Windows 10/11 doesn't scale with many modern UIs like Telegram.

## Steps
Download the .reg file and open it, click Yes to confirm then restart your computer.

## Current draw backs 
- ~~Browsers not selecting the right fallback font~~ Install fonts for **All users**

## Other Methods
- https://www.rean.me/2021/10/how-to-fix-khmer-unicode-display-on-facebook-and-youtube.html
- https://commerce-cambodia.com/2021/06/11/fix-tiny-khmer-font-size-on-telegram-for-desktop/
  - I would advise against this one, many old windows programs, *cough* Nvidia Control Panel *cough* cannot scale correctly with Khmer Unicode width. This cause some content to be out of bounds and windows will not scroll correctly
