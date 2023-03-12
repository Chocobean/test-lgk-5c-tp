
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
agent.
if(agent.inspect(AgentInspection.Block, FORWARD) == 0)

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

Die Aufgabe besteht darin, euren ``||agent:Agent||`` von einer Seite eurer 
Arbeitsfläche zur anderen Seite zu bewegen und zwar von links unten nach links oben.

Der ``||agent:Agent||``  soll dabei die ``||loops:Arbeitsfläche||``  nicht verlassen!

Beantwortet die Frage auf dem Aufgabenblatt.

Meldet euch bei eurem ``||player:Lehrer||`` falls ihr die Aufgabe abgeschlossen habt!

Wenn ihr Hilfe benötigt, könnt ihr die Glührbirne unten anklicken.

### ~ tutorialhint 

Ihr braucht die folgende Blöcke um die Aufgabe zu lösen.

```blocks
agent.teleport(world())
agent.move()
```
## Den Agent im Kreis laufen lassen

Nachdem ihr die vorherige Aufgabe gelöst habt, sollt ihr nun euren Code
soweit erweitern sodass der ``||agent:Agent||`` einmal komplett im Kreis läuft.

Achtet darauf dass der ``||agent:Agent||`` die ``||loops:Arbeitsfläche||`` nicht verlässt.

Beantwortet die Frage auf dem Aufgabenblatt.

Meldet euch bei eurem ``||player:Lehrer||`` falls ihr die Aufgabe abgeschlossen habt!

Wenn ihr Hilfe benötigt, könnt ihr die Glührbirne unten anklicken.

### ~ tutorialhint 

Ihr braucht die folgende Blöcke um die Aufgabe zu lösen.

```blocks
agent.teleport(world())
agent.move()
agent.turn()
```

## Den Agent im Kreis laufen lassen (Erweitert)

Überlegt nun wie ihr den Code aus der vorherigen Aufgabe verbessern (optimieren) könnt.

Beantwortet die Frage auf dem Aufgabenblatt.

Meldet euch bei eurem ``||player:Lehrer||`` falls ihr die Aufgabe abgeschlossen habt!

Wenn ihr Hilfe benötigt, könnt ihr die Glührbirne unten anklicken.

### ~ tutorialhint 

Ihr braucht unter anderem den folgenden Block um die Aufgabe zu lösen.

```blocks
for (let index = 0; index < ; index++) {}
```
Ihr müsst nun noch herausfinden, wieviel mal die Aktion wiederholt werden muss.

## Erste Blöcke mit dem Agent platzieren

Nachdem euer Code nun optimiert ist, soll euer ``||agent:Agent||`` nun in jeder Ecke einen Block setzen.

Erweitert dementsprechend euren Code. Schaut euch das Beispiel auf dem Aufgabenblatt an.

Meldet euch bei eurem ``||player:Lehrer||`` falls ihr die Aufgabe abgeschlossen habt!

Wenn ihr Hilfe benötigt, könnt ihr die Glührbirne unten anklicken.

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
## Arbeitsfläche füllen

Da ihr nun wisst wie ihr Blöcke setzen könnt, soll euer ``||agent:Agent||`` nun
die gesamte ``||loops:Arbeitsfläche||`` mit Blöcken befüllen. Die Wahl des Blockes welcher platziert wird
ist euch überlassen.

Ihr müsst bei dieser Aufgabenstellung einiges bedenken, da der ``||agent:Agent||``
sich nun in 2 Richtungen bewegen muss.

Meldet euch bei eurem ``||player:Lehrer||`` falls ihr die Aufgabe abgeschlossen habt!

Wenn ihr Hilfe benötigt, könnt ihr die Glührbirne unten anklicken.

### ~ tutorialhint 
Überlegt euch wie ihr eine Seite komplett füllen könnt. Dannach müsst ihr nur noch die Aktion 
solange wiederholen bis eure Arbeitsfläche komplett gefüllt ist.

## Schachbrett bauen

Als letzte Aufgabe soll euer ``||agent:Agent||`` nun ein Schachbrett bauen.

Wie ihr sicher wisst besteht ein Schachbrett aus 2 Farben (Weiß und Schwarz), sowie aus 8 x 8 Feldern. Ihr
könnt die Farben für euer Schachbrett frei wählen, umso eurem Schachbrett eine persönliche Note zu verleihen.

Achtet darauf dass der ``||agent:Agent||`` die ``||loops:Arbeitsfläche||`` nicht verlässt.

Meldet euch bei eurem ``||player:Lehrer||`` falls ihr die Aufgabe abgeschlossen habt!

Wenn ihr Hilfe benötigt, könnt ihr die Glührbirne unten anklicken.

### ~ tutorialhint 
Überlegt euch wie ihr zwischen Blöcken wechseln könnt. Dannach ist die Aufgabe der vorherigen sehr ähnlich!
