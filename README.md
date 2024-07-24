# dojo-lobby
Exploring code for a standard game lobby in Dojo

Much code is referenced from the game and based devs at [Pistols at 10 Blocks](https://github.com/underware-gg/pistols). Without this, life is just crazy if u know what i mean.

#### Model Assumptions
- Player model tagged to unique wallet address (or mapped)
- Game Room model tracks individual game room systems and Game Room System enforces necessary duplication logics
- Global list of players can be queried via front-end
- Room matching can be done by front-end query matching


#### Bones of a Lobby

- [ ] Game Rooms List (in-progress, awaiting, expired, withdrawn(closed), completed)
- [ ] Room Creation (+ various room configs)
  - [ ] Room expiration?
- [ ] Challenge Room / Registration to Room's Game
- [ ] Logic for Room occupation (can player be in multiroom at once)
  
#### Game Room Bones
- [ ] Room Owner Acceptance (or Auto Accept)
- [ ] Room Owner can invite specific player for challenge
- [ ] Owner close Room (all boot)
- [ ] Participant Leave Room
- [ ] Player Pre-game configurations?
- [ ] Game Start condition (or Auto Start)
