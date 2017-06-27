.. _installation:

=============
Установка Git
=============

Windows
-------
1. Скачайте и установите SSH-клиент PuTTY: http://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
2. Скачайте и установите текстовый редактор Notepad++: https://notepad-plus-plus.org/
3. Скачайте установочный дистрибутив со страницы https://git-scm.com/download/win
4. Запустите скачанный исполняемый файл, например Git-2.13.2-64-bit.exe
5. Следуйте инструкциям, которые предлагает мастер по установке

При этом обратите внимание на следующие параметры:

.. figure:: images/windows_installation_01.png
    :figclass: align-center

    Установка Git в ОС Windows

.. figure:: images/windows_installation_02.png
    :figclass: align-center

    Выбор расположения для установки

.. figure:: images/windows_installation_03.png
    :figclass: align-center

    Рекомендуемые параметры интеграции с Windows Explorer

.. figure:: images/windows_installation_04.png
    :figclass: align-center

    Расположение в меню Пуск

.. figure:: images/windows_installation_05.png
    :figclass: align-center

    Рекомендуемые параметры интеграции с Windows Command Prompt

.. figure:: images/windows_installation_06.png
    :figclass: align-center

    Рекомендуемые настройки для работы с протоколом HTTPS

.. figure:: images/windows_installation_07.png
    :figclass: align-center

    Рекомендуется включить автоматическую конвертацию окончаний строк (CRLF -> LF)

.. figure:: images/windows_installation_08.png
    :figclass: align-center

    Для работы с Git Bash рекомендуется использовать терминал MinTTY

.. figure:: images/windows_installation_09.png
    :figclass: align-center

    Данные опции по умолчанию рекомендуется оставить включенными

.. figure:: images/windows_installation_10.png
    :figclass: align-center

    Установка

.. figure:: images/windows_installation_11.png
    :figclass: align-center

    Установка завершена

----

Windows (установка при помощи Scoop)
------------------------------------
Для установки Git в операционной системе Windows можно воспользоваться менеджером пакетов Scoop.

1. Если у вас не установлен менеджер пакетов Scoop, то сделайте это при помощи оффициального скрипта установки:

.. code-block:: powershell

  # данную команду необходимо ввести в приложении "PowerShell"

  iex (new-object net.webclient).downloadstring('https://get.scoop.sh')

2. При помощи пакетного менеджера Scoop установите Git:

.. code-block:: powershell

    # данную команду необходимо ввести в приложении "PowerShell"

    scoop install git

Ubuntu Linux
------------
Для установки Git воспользуйтесь стандартным пакетным менеджером APT:

.. code-block:: bash

   apt update && apt install git

macOS (установка при помощи Homebrew)
---------------------------------------------
Для установки Git в операционной системе macOS рекомендуется воспользоваться менеджером пакетов Homebrew.

1. Если у вас не установлен менеджер пакетов Homebrew, то сделайте это при помощи `оффициального скрипта установки <https://raw.githubusercontent.com/Homebrew/install/master/install>`_:

.. code-block:: bash

  # данную команду необходимо ввести в приложении "Терминал"

  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  
2. При помощи пакетного менеджера Homebrew установите Git:

.. code-block:: bash

    # данную команду необходимо ввести в приложении "Терминал"

    brew install git

Теперь вы можете перейти к :ref:`первоначальной настройке <configuration>`.

.. index:: PuTTY, Notepad++, Windows, Scoop, PowerShell, Ubuntu, Linux, apt, macOS, Homebrew, brew
