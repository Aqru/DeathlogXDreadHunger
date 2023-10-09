# DeathlogXDreadHunger

## RU
Добавление в аддон Deathlog звук смерти из Dread Hunger.

### Быстрая установка

Достаточно скачать [Deathlog.zip](/Deathlog.zip), разархивировать его и положить в `World of Warcraft\_classic_era_\Interface\AddOns\`. 

Если аддон уже использовался ранее, нужно сбросить его настройки, для этого в настройках самого аддона:
- в разделе `minilog` нажать `Reset to default`
- в разделе `DeathAlert` нажать `Reset to default`

### Ручная установка

*TBD:* пока тут только настройка звука, добавление поддержки локализации и специальный эффект для оповещения о смерти от Сына Аругала тут не описан из-за слишком большого количества изменений в файлах аддона. 

Предпологается, что аддон уже установлен.

1. Для начала нужно отредактировать файл аддона:
   - В `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Widgets\DeathAlert\widget.lua` добавить после 19 строки:
	`sounds["Dread_Hunger"] = "Interface\\AddOns\\Deathlog\\Sounds\\Dread_Hunger.ogg"`

1. В `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Sounds` добавить новый звук алерта [Dread_Hunger.ogg](/Dread_Hunger.ogg)
	
После этого в настройках аддона можно будет выбрать этот звук.

### Примечания

Файл [Deathlog.zip](/Deathlog.zip) актуален для версии аддона `0.1.10` (6 октября 2023 года).

## EN
Adding the sound of death from Dread Hunger to the Deathlog addon.

### Quick installation

Just download [Deathlog.zip](/Deathlog.zip), unzip it and put it in `World of Warcraft\_classic_era_\Interface\AddOns\`.

### Manual installation

It is assumed that the addon is already installed.

1. First you need to edit the addon file:
    - In `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Widgets\DeathAlert\widget.lua` add after line 19:
`sounds["Dread_Hunger"] = "Interface\\AddOns\\Deathlog\\Sounds\\Dread_Hunger.ogg"`

1. In `World of Warcraft\_classic_era_\Interface\AddOns\Deathlog\Sounds` add a new alert sound [Dread_Hunger.ogg](/Dread_Hunger.ogg)

### Notes

The file [Deathlog.zip](/Deathlog.zip) is relevant for the addon version `0.1.10` (October 6, 2023).
