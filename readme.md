# Zombie Cows
A mini-project that we worked on during our *Logic Programming* workshop at INSAT.
<br>
It is implemented in Prolog using __SWI Prolog__!

## To play:
Open SWI Prolog and consult the file.
<br>
Type *jouer*.
<br>
And then type either *nord*, *sud*, *est*, *west* or *reste*.

## Flowchart

```mermaid
graph TD
A((jouer.)) --> B{Direction?}
B -- !touch_zombie --> C(move)
C --> B
B -- touch zombie --> D[\Dimitri dies\]
D --> E((end))
```

## Demo:

 <p align="center">
  <img src="https://github.com/hajali-amine/DimitriAndTheZombieCows/blob/main/demo.gif" alt="animated" />
</p>

## Have fun!