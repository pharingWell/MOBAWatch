# MOBAWatch

### Index

- [What is MOBAWatch?](https://github.com/pharingWell/MOBAWatch#what-is-mobawatch)

- [Progress](https://github.com/pharingWell/MOBAWatch#whats-the-progress-look-like)

- [Get in touch](https://github.com/pharingWell/MOBAWatch#how-can-i-get-in-touch-with-you)

- [Playing the mode](https://github.com/pharingWell/MOBAWatch#how-do-I-run-it)

- [Editing the source](https://github.com/pharingWell/MOBAWatch#how-do-i-edit-it)

---

### What is MOBAWatch?

  MOBA is an attempt to make a 1 lane ARAM (All Random, All Mid) version of a MOBA within Overwatch's "Workshop" system.
This project accomplishes this by:
 1. Transferring player look angle to 2D movement
 2. Creating a "dummy" bot for each player to enact their actions in their stead
 3. Simulating minions using in-world text, effects and a large array with which to store their information
 4. Simulating structures using a similar system
 5. Altering player abilities to best fit the new perspective
 6. Disabling or limiting specific heroes which would be too costly to manage

---
### What's the code structure?
![image](https://user-images.githubusercontent.com/30706897/232511265-335cd23f-5e9e-4d6e-9435-5de5e433b16b.png)

---

### What's the progress look like?

- [ ] Make 2D view mode
- [ ] Link Dummy Bots to players
- [ ] Simulate Minions:
  - [x] Are created
  - [x] Simulate movement
  - [ ] Take damage
  - [ ] Can be targeted
  - [ ] Are destroyed
  - [ ] Can be affected player abilities (Ice Wall, Graviton Surge)
- [ ] Create structures
- [x] Make lane
  - [ ] Lane collisions/bounds
  - [ ] Small jungle
    - [ ] Implement brutes/some jungle reward
- [ ] Translate Heroes
  - [ ] Targeting system / basic attacks
  - [ ] Implement mana
  - [ ] Can take/deal damage
    - [ ] Damage abstraction
  - [ ] Damage over time/healing over time
  - [ ] Basic attacks
     - [ ] Auto lock option
  - [ ] Visibility
- [ ] UI

---

### How can I get in touch with you?

Create an issue on this repository or add me on discord @pharingwell.

---

### How do I run it?

There is currently no stable version, but you can check out a demo of the grid system with this code: `894P4`

---

### How do I edit it?

  First, get [OSTW](https://github.com/ItsDeltin/Overwatch-Script-To-Workshop).

Follow the instructions on how to compile, and modify or edit it to your heart's content. [^1]

[^1]: You must keep both the link to this github, and the original author's name (pharingwell) in the project files.
