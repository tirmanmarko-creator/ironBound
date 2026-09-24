# ironBound

A text-based CLI RPG, written in Java.

> **Status:** Early development. This README will grow as the project does.

## About

I am building this game as a personal project to practice Java, object-oriented design, and working with Maven and Git. The plan is to keep it small, playable, and finished, then add features one at a time.

## Goals

### Learning goals

- [ ] Design a project with clear classes and responsibilities
- [ ] Use inheritance and interfaces in a real program
- [ ] Save and load data from files
- [ ] Write unit tests with JUnit
- [ ] Keep a clean Git history with meaningful commits

### Game goals

- [ ] Move between connected rooms
- [ ] Turn-based combat (attack, defend, use item)
- [ ] Inventory with weapons, armor, and potions
- [ ] Character classes (e.g. Warrior, Mage)
- [ ] Random events and loot drops
- [ ] Save and load the game

### Stretch goals

- [ ] More enemies, rooms, and classes
- [ ] Simple story or quests
- [ ] Optional JavaFX interface
### Project Structure

'src/
├── main/java/[package]/
│   ├── Main.java          # Entry point and game loop
│   ├── characters/        # Player, Enemy, character classes
│   ├── items/              # Weapons, armor, potions
│   ├── world/               # Rooms and map
│   └── storage/           # Save / load logic
└── test/java/[package]/   # JUnit tests

pom.xml                    # Maven project config'

## Tech Stack

- Java 17+
- Maven
- JUnit

## Getting Started

```bash
git clone https://github.com/[your-username]/[repo-name].git
cd [repo-name]
mvn clean package
java -jar target/[artifact-name]-1.0.jar
```

> These commands will work once the first playable version exists.

## Author

**Marko Tirman**
GitHub: (https://github.com/tirmanmarko-creator)
