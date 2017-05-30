.. _installation:

=============
Установка Git
=============

Windows
-------
1. Скачайте и установите SSH-клиент PuTTY: http://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
2. Скачайте установочный дистрибутив со страницы https://git-scm.com/download/win
3. Запустите скачанный исполняемый файл, например Git-2.11.0-64-bit.exe
4. Следуйте инструкциям, которые предлагает мастер по установке

При этом обратите внимание на следующие параметры:

.. figure:: images/windows_installation_01.png
    :figclass: align-center

    Установка Git в ОС Windows

.. figure:: images/windows_installation_02.png
    :figclass: align-center

    Рекомендуемые параметры интеграции с Windows Explorer

.. figure:: images/windows_installation_03.png
    :figclass: align-center

    Рекомендуемые параметры интеграции с Command Prompt

.. figure:: images/windows_installation_04.png
    :figclass: align-center

    Для работы с удаленными Git-репозиториями по протоколу SSH рекомендуется использовать PuTTY

.. figure:: images/windows_installation_05.png
    :figclass: align-center

    Рекомендуется включить автоматическую конвертацию окончаний строк (CRLF -> LF)

.. figure:: images/windows_installation_06.png
    :figclass: align-center

    Для работы с Git Bash по умолчанию рекомендуется использовать MinTTY

.. figure:: images/windows_installation_07.png
    :figclass: align-center

    Данные опции по умолчанию рекомендуется оставить включенными

.. figure:: images/windows_installation_08.png
    :figclass: align-center

    Новый, экспериментальный инструмент сравнения по умолчанию

.. figure:: images/windows_installation_09.png
    :figclass: align-center

    Установка завершена

----

Ubuntu Linux
------------
Для установки Git воспользуйтесь стандартным пакетным менеджером APT:

.. code-block:: bash

   sudo apt update && sudo apt install git

macOS
-----
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

.. index:: Windows, Ubuntu, Linux, macOS, PuTTY, apt, Homebrew, brew
