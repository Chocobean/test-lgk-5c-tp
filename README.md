# 5C - TP
<!-- block combinations that will show up by default in their workspace -->
```template
agent.teleportToPlayer()
```

<!-- blocks you want available to players, based on js code -->
```blocks
player.say(":)")
player.onTravelled(WALK, function () {})
player.onChat("run", function () {})

agent.setItem(GRASS, 1, 1)
agent.teleport(world(0, 0, 0), WEST)
agent.teleportToPlayer()
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.place(FORWARD)
agent.destroy(FORWARD)
agent.collectAll()
agent.
if(agent.inspect(AgentInspection.Block, FORWARD) == 0)
if(agent.getPosition() == 0)
if(agent.detect(AgentDetection.Block, FORWARD) == 0)
agent.drop(FORWARD, 1, 1)

while (false) {}
if(true) {} else {}
for (let index = 0; index < 4; index++) {}

if(0 == 0)
if(randint(0, 10) == 0)
if(variable)

world(0,0,0)

```

# Intro

## Intro step @showdialog

![Lights flashing](/static/giphy.gif)

## Erstes  Programm! @unplugged

Hallo test

Rechts findet ihr ein erstes Beispielprogramm.

Startet nun das Programm unten rechts und schaut was passiert!

Antwortet auf die Frage auf eurem Arbeitsblatt!

Schaut euch auch die restlichen Codeblöcke an und versucht zu verstehen was diese machen.


  - :blank: Bullet 1
  - :mouse pointer: Bullet 2

``||on start|``

``||agent teleport to player||``

![Agent building a tower](/static/giphy.gif)

## Den Agent bewegen

Nun ist es an der Zeit euer erstes Programm zu erstellen.

Die Aufgabe besteht darin euren Agent von einer Seite eurer 
Arbeitsfläche zur anderen Seite zu bewegen und zwar von links unten nach links oben.

Falls du Hilfe benötigst kannst du auf die Glühbirne unten klicken.

Melde dich bei deinem Lehrer falls du die Aufgabe abgeschlossen hast!

## Introduction 

Have the agent build a tower! Make a command to tell it how many levels to build.

gdfgdfgdfgdfgadg
gdfgdfgdfgdfgadggdfgdfgd



