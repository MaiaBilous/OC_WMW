> Роботу виконували: Білоус Майя, Коломієць Артем, Танєєва Анастасія


> Виконувала Білоус Майя

1. В робочому середовищі віртуальної машини Virtual Box, VMWare Workstation (або інший на Ваш вибір) необхідно виконати:
- Клонування вашої віртуальної робочої ОС (Work-case 2). Яким чином це можна зробити? Продемонструйте всі етапи;

Для цього треба спочатку запустити VMware Fusion

![image](https://github.com/user-attachments/assets/970e5e66-72ce-48f7-b18d-393b82cf49d1)

Вибрати потрібну віртуальну машину та клацнути по ній провою кнопкою миші

![image](https://github.com/user-attachments/assets/ac2ab386-8f17-4bba-88e3-4a07107ad9c9)

З'явиться вікно, яке запропонує вибір між "Linked Clone" і "Full Clone":
- Linked Clone — це клон, який залежить від оригінальної віртуальної машини. Зміни в оригінальній машині можуть вплинути на клон.
- Full Clone — це незалежний клон, який створює точну копію оригіналу, і зміни в оригіналі не впливають на клон.

Треба вибрати потрібне клонування, назвати нову віртувальну машину та натиснути "Зберегти"

![image](https://github.com/user-attachments/assets/7f12dd30-85ce-4208-a96a-2ccad7027406)

Після цього з'явиться робочий клон віртуальної машини

![image](https://github.com/user-attachments/assets/59ff01a7-6c12-4b93-9e25-354460e2face)
  
- Може виникнути необхідність перенесення (клонування) ОС у інше віртуальне середовище. Які треба виконати дії для експорту вашої віртуальної робочої ОС?

Для цього треба вибрати віртуальну машину та натиснути "File" після чого "Export to OVF..."

![telegram-cloud-photo-size-2-5375587978732239102-x](https://github.com/user-attachments/assets/efba4ada-d37b-4582-be8e-ede84c85892e)


> Виконувала Танєєва Анастасія

2. Визначте який менеджер пакетів використовує ваш дистрибутив Linux. Опишіть основні команди для роботи з ним:

2.1 Пошук, скачування та установка пакетів

*Searching for a package: **apt search <package_name>**
*Installing a package: **sudo apt install <package_name>**
*Adding a new repository: **sudo add-apt-repository ppa:<name>
sudo apt update**
*Installing from a local .deb package: **sudo dpkg -i <file.deb>
sudo apt install -f**

2.2 Перегляд інформації про встановлені та доступні пакети.


> Виконував Коломієць Артем
4. Яким чином можна організувати обмін інформацією між вашою основною ОС (наприклад Windows) 
та віртуальними ОС? Скопіюйте довільний аудіо-файл з вашої основної ОС на робочий стіл віртуальної
ОС та її клона. Як зробити зворотну дію, коли треба документ з робочого столу віртуальної ОС скопіювати до вашої основної робочої ОС?
(Virtual Box,ubuntu.)

1.
First, you need to create a shared folder.
Create a shared folder in the VirtualBox settings
Virtual Box settings - Shared folders - Machine folders
Click on the folder with a plus sign (Add new shared Folder)

Click Add New Shared Folder (folder icon with a plus sign).
Select the folder (C:\1234\prgm\shared_WMW).
Next, in the Mount Point field, specify the path to the file
Enable the Auto-mount and Make Permanent options.
start the virtual machine. 
Connecting a shared folder in Ubuntu
you need to use the command 

sudo mount -t vboxsf ( name of shared folder in virtual box) (path)
sudo mount -t vboxsf shared_WMW /mnt/shared_WMW
Copy the audio file to the virtual OS 

cp /mnt/shared_WMW/audio.mp3 ~/Desktop/

2.
Copy a document from the virtual OS to the main OS
Move the document to the shared folder:

cp ~/Desktop/OC_WMW_text.txt /mnt/shared_WMW/
open C:\1234\prgm\shared_WMW and find OC_WMW_text.txt 
