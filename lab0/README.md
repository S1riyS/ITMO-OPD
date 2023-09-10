[![bw-w-eng.jpg](https://i.postimg.cc/WzqmKdFN/bw-w-eng.jpg)](https://postimg.cc/K3Fg3vDw)

<p align="left">
Выполнил: <strong>Анкудинов Кирилл</strong></br>
Группа: <strong>P3118</strong></br>
Вариант: <strong>11601</strong>
</p>

# Лабораторная работа №0

## 📝 Ход работы

1. Создать приведенное в варианте дерево каталогов и файлов с содержимым.
   В качестве корня дерева использовать каталог lab0 своего домашнего каталога.
   Для создания и навигации по дереву использовать команды: mkdir, echo, cat, touch, ls, pwd, cd, more, cp, rm, rmdir,
   mv.
   
   [![image.png](https://i.postimg.cc/q7Zmmmgh/image.png)](https://postimg.cc/Z9pFnx84)

* Каталоги и файлы первого уровня:
    ```shell
    [s413732@helios ~/OPD/lab0]$ touch glalie4
    [s413732@helios ~/OPD/lab0]$ mkdir gothorita1
    [s413732@helios ~/OPD/lab0]$ mkdir gulpin3
    [s413732@helios ~/OPD/lab0]$ touch kabutops7
    [s413732@helios ~/OPD/lab0]$ touch nidoqueen3
    [s413732@helios ~/OPD/lab0]$ mkdir serperior2
    ```

* Каталоги и файлы второго уровня:
    
    ```shell
    [s413732@helios ~/OPD/lab0]$ cd gothorita1
    [s413732@helios ~/OPD/lab0/gothorita1]$ touch whiscash
    [s413732@helios ~/OPD/lab0/gothorita1]$ mkdir swadloon
    [s413732@helios ~/OPD/lab0/gothorita1]$ touch braviary
    [s413732@helios ~/OPD/lab0/gothorita1]$ mkdir hippowdon
    
    [s413732@helios ~/OPD/lab0/gothorita1]$ cd ../gulpin3
    [s413732@helios ~/OPD/lab0/gulpin3]$ touch piloswine
    [s413732@helios ~/OPD/lab0/gulpin3]$ mkdir medicham
    [s413732@helios ~/OPD/lab0/gulpin3]$ touch lilligant
    [s413732@helios ~/OPD/lab0/gulpin3]$ touch prinplup
    
    [s413732@helios ~/OPD/lab0/gulpin3]$ cd ../serperior2
    [s413732@helios ~/OPD/lab0/serperior2]$ mkdir magcargo
    [s413732@helios ~/OPD/lab0/serperior2]$ mkdir tentacool
    [s413732@helios ~/OPD/lab0/serperior2]$ touch wartortle
    [s413732@helios ~/OPD/lab0/serperior2]$ mkdir pignite
    [s413732@helios ~/OPD/lab0/serperior2]$ touch gengar
    ```
* Наполнение файлов:
    ```shell
    [s413732@helios ~/OPD/lab0]$ cat >glalie4
    Xoды Avalanche Block Body Slam Dark Pulse Double-Edge Icy
    Wind Iron Head Rollout Signal Beam Sleep Talk Snore Spite Super Fang
    Water Pulse
    
    [s413732@helios ~/OPD/lab0]$ cat >gothorita1/whiscash
    Xoды Aqua Tail Bounce Dive Double-Edge Earth        
    Power Icy Wind Mud-Slap Sleep Talk Snore Tickle‡ Zen
    Headbutt‡
  
    [s413732@helios ~/OPD/lab0]$ cat >gothorita1/braviary 
    Живет Forest Mountain
  
    [s413732@helios ~/OPD/lab0]$ cat >gulpin3/piloswine 
    Живет Cave
    Taiga Tundra
  
    [s413732@helios ~/OPD/lab0]$ cat >gulpin3/lilligant 
    Тип покемона GRASS NONE
  
    [s413732@helios ~/OPD/lab0]$ cat >gulpin3/prinplup 
    Способности
    Growl Bubble Water Sport Peck Metal Claw Bubblebeam Bide Fury Attack
    Brine Whirlpool Mist Drill Peck Hydro Pump
  
    [s413732@helios ~/OPD/lab0]$ cat >kabutops7 
    Тип диеты
    Omnivore
  
    [s413732@helios ~/OPD/lab0]$ cat >nidoqueen3 
    satk=8 sdef=9 spd=8
  
    [s413732@helios ~/OPD/lab0]$ cat >serperior2/wartortle 
    Способности Tail
    Whip Bubble Withdraw Water Gun Bite Rapid Spin Protect Water Pulse
    Aqua Tail Skull Bash Iron Defense Rain Dance Hydro Pump
    
    [s413732@helios ~/OPD/lab0]$ cat >serperior2/gengar 
    Тип
    покемона GHOST POISON
    ```

