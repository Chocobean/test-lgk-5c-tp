
### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @hideIteration true 
### @explicitHints 1

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

## Erstes  Programm!

Rechts findet ihr ein erstes Beispielprogramm.

Startet nun das Programm unten rechts und schaut was passiert!

Antwortet auf die Frage auf eurem Arbeitsblatt!

Schaut euch auch die restlichen Codeblöcke an und versucht zu verstehen was diese machen.


## Den Agent bewegen


Nun ist es an der Zeit euer erstes Programm zu erstellen.

Die Aufgabe besteht darin euren ``||agengt:Agent||`` von einer Seite eurer 
Arbeitsfläche zur anderen Seite zu bewegen und zwar von links unten nach links oben.

Der Agent soll dabei die Arbeitsfläche nicht verlassen!

Wenn ihr Hilfe benötigt, könnt ihr Glührbirne unten anklicken.

Beantwortet die Frage auf dem Aufgabenblatt.

Meldet euch bei eurem Lehrer falls ihr die Aufgabe abgeschlossen habt!

### ~ tutorialhint 

Ihr braucht die folgende Blöcke um die Aufgabe zu lösen.

```blocks
agent.teleport(world())
agent.move()
```
## Den Agent im Kreis laufen lassen

Nachdem ihr die vorherige Aufgabe gelöst habt, sollt ihr nun euren Code
soweit erweitern sodass der Agent einmal komplett im Kreis läuft.

Achtet darauf dass der Agent die Arbeitsfläche nicht verlässt.

Beantwortet die Frage auf dem Aufgabenblatt.

Meldet euch bei eurem Lehrer falls ihr die Aufgabe abgeschlossen habt!

### ~ tutorialhint 

Ihr braucht die folgende Blöcke um die Aufgabe zu lösen.

```blocks
agent.teleport(world())
agent.move()
agent.turn()
```

## Den Agent im Kreis laufen lassen (Erweitert)

Überlegt nun wie ihr den Code aus der vorherigen Aufgabe verbessern (optimisieren) könnt.

Beantwortet die Frage auf dem Aufgabenblatt.

Meldet euch bei eurem Lehrer falls ihr die Aufgabe abgeschlossen habt!

## Erste Blöcke mit dem Agent platzieren

Nachdem euer Code nun optimiert ist, soll euer Agent nun in jeder Ecke einen Block setzen.

Erweitert dementsprechend euren Code. Schaut euch das Beispiel auf dem Aufgabenblatt an.

### ~ tutorialhint 
Bevor ein Agent einen Block setzen kann, muss sich der Block in seinem Inventar befinden, und zwar auf der 1. Position (Slot).
In diesem Beispiel wird dem Agent 1 Grasblock auf Position 1 hinzugefügt.

```blocks
agent.setItem(GRASS, 1, 1)
```

Um einen Block zu setzen müsst ihr den folgenden Befehl benutzen:

```blocks
agent.place()
```


