# DeathlogXDreadHunger

## RU
Добавление в аддон Deathlog звук смерти из Dread Hunger.

### Установка

Предпологается, что аддон уже установлен.

1. Для начала нужно отредактировать файл аддона, есть два варианта:
   - Можно просто заменить файл `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Widgets\DeathAlert\widget.lua` на [widget.lua](/widget.lua) 
   - В `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Widgets\DeathAlert\widget.lua` добавить после 19 строки:
	`sounds["Dread_Hunger"] = "Interface\\AddOns\\Deathlog\\Sounds\\Dread_Hunger.ogg"`

1. В `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Sounds` добавить новый звук алерта [Dread_Hunger.ogg](/Dread_Hunger.ogg)
	
После этого в настройках аддона можно будет выбрать этот звук.

### Примечания

Файл [widget.lua](/widget.lua) актуален для версии аддона `0.1.10` (6 октября 2023 года).

## EN
Adding the sound of death from Dread Hunger to the Deathlog addon.

### How to setup

It is assumed that the addon is already installed.

1. First you need to edit the addon file, there are two options:
    - You can simply replace the file `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Widgets\DeathAlert\widget.lua` with [widget.lua](/widget.lua)
    - In `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Widgets\DeathAlert\widget.lua` add after line 19:
`sounds["Dread_Hunger"] = "Interface\\AddOns\\Deathlog\\Sounds\\Dread_Hunger.ogg"`

1. In `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Sounds` add a new alert sound [Dread_Hunger.ogg](/Dread_Hunger.ogg)

### Notes

The file [widget.lua](/widget.lua) is relevant for the addon version `0.1.10` (October 6, 2023).
