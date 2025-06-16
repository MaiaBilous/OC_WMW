> Роботу виконували: Білоус Майя, Коломієць Артем, Танєєва Анастасія

> Виконувала Танєєва Анастасія

1. В ході роботи досить часто виникає необхідність встановлювати нові програми та додатки. Для цього необхідно в терміналі вміти працювати з менеджерами пакетів:

- Дайте розгорнуте визначення таким поняттям як «пакет» та «репозиторій».

A repository is a centralized, usually remote, Internet-based repository that contains an organized collection of software packages, their metadata, and digital signatures. It is the primary source of software for an operating system.

Key characteristics of repositories:

Software source: It is from repositories that the operating system obtains all of its programs and updates.
Organization: Packages in repositories are structured by system architecture (e.g., amd64, arm64) and distribution version, ensuring compatibility.
Reliability and security: Official repositories are maintained by the distribution's developers. They guarantee stability, compatibility, and the absence of malicious components, as all packages are thoroughly tested.
Mirrors: "Mirrors" are used to optimize access speed and load distribution, which are complete copies of the repositories located on different servers around the world.
Types of repositories:
Main: Contains free and open source software that is officially supported by the distribution's developers.
Limited: Includes proprietary software or drivers that are not fully free but are often necessary for the system to function properly (e.g., video card drivers).
Universe: A large collection of software maintained by the community rather than by official developers.
PPA: Allows users or small teams to contribute their own packages that are not included in the official repositories.
  
- Надайте короткий огляд існуючих менеджерів пакетів у Linux. Охарактеризуйте їх основні можливості.

  A package manager is a system tool that automates the entire software management cycle: from installation and configuration to updating and uninstalling. It is an intermediary between the user, the system and the repositories.

The main features of package managers include:

Installing and uninstalling programs.
Comprehensive updating of installed packages and the operating system.
Searching for programs by various criteria.
Automatic resolution and installation of necessary dependencies.
Checking the integrity and authenticity of downloaded packages.
Management of available repositories.
Common package managers:
1. APT (Advanced Package Tool)
Used in Debian, Ubuntu, Linux Mint and derivative distributions, works with .deb format packages. APT allows you to update package indexes, update the entire system, install and uninstall programs. It also automatically removes unnecessary dependencies and provides detailed information about packages.

2. DNF (Dandified YUM)
Inherent in Fedora, CentOS, Red Hat Enterprise Linux and other Red Hat-based distributions. It manages .rpm packages. DNF performs updates, installs and removes programs, and also supports searching and displaying information. DNF is the successor to YUM, which solved many problems with dependency resolution.

3. Pacman
The main package manager for Arch Linux and Manjaro, works with .pkg.tar.xz packages. Pacman is noted for its speed and simplicity. It allows you to synchronize databases and update the entire system, install and remove packages. It also supports searching and displaying detailed information.

4. Zypper
Used in openSUSE and SUSE Linux Enterprise, operates on .rpm packages. Zypper allows you to update packages, install and remove them. It also supports searching and displaying information, as well as updating repositories. Zypper is known for its reliable repository management system and integrated dependency conflict resolution.

> Виконував

> Виконувала Білоус Майя

2. Визначте який менеджер пакетів використовує ваш дистрибутив Linux. Опишіть основні команди для роботи з ним:
- Пошук, скачування та установка необхідних пакетів, яких у Вашій системі немає (зі сховища по замовчуванню, з нового репозиторію тощо).

Менеджером пакетів є APT (Advanced Packaging Tool)

Пошук: sudo apt search

Скачування: sudo apt install

Установка: sudo add-apt-repository ppa: -> sudo apt update -> sudo apt install

- Перегляд інформації про встановлені та доступні пакети - apt show

- Видалення непотрібних або застарілих пакетів - sudo apt remove

- Оновлення менеджера пакетів - sudo apt update

3. Встановіть у терміналі через менеджер пакетів на свою систему:
   
- Новий відео- чи аудіоплейер.
  
![image](https://github.com/user-attachments/assets/251ac42f-8091-44aa-b8eb-eea79b5e2bad)

![image](https://github.com/user-attachments/assets/c310bc44-2a7f-4299-96f0-3092783516e8)

![image](https://github.com/user-attachments/assets/990cb451-5fa7-444f-b224-834bab1a701a)

![image](https://github.com/user-attachments/assets/d5d0da11-7e19-4836-91b8-c7b829807ab7)

- Середовище для мови програмування, що ви вивчаєте.

![image](https://github.com/user-attachments/assets/1aa17d79-92df-410b-adab-76084e49c923)

