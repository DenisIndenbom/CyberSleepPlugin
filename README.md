# CyberSleepPlugin
CyberSleep is a plugin for skipping boring nights.

When a certain percentage (for example, 40%) of players are asleep, the plugin skips the night.

The plugin also shows how many players and how many players are needed to skip the night.

![image](https://user-images.githubusercontent.com/59681620/145094592-b717290f-3b73-47f5-ab92-ec6459915186.png)

### Example config.yml
```yml
# <playerName> - player name
# <c > - specifying the color
# <c0> - black
# <c1> - dark blue
# <c2> - dark green
# <c3> - dark aqua
# <c4> - dark red
# <c5> - dark purple
# <c6> - gold
# <c7> - gray
# <c8> - dark gray
# <c9> - blue
# <ca> - green
# <cb> - aqua
# <cc> - red
# <cd> - light purple
# <ce> - yellow
# <cf> - white

# config version
config_version: 1

# messages
messages:
  helpMessage: This is a <c5>CyberSleepPlugin. <cf>The plugin helps to skip boring nights!
  enterBedMessage: <c7>Good night <playerName>!
  exitBedMessage: <c7>Good morning <playerName>!
  reloadMessage: <c5>CyberSleepPlugin <cf>reloaded!

sleeping_bar:
  title: <c9>Sleeping
  color: blue


max_percent_of_sleeping_players: 0.3 # диопозон от 0 до 1
```
