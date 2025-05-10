#IT265 Final Game Design Document

---
## Change Log
1. Smaller scope: I didn't have time to complete so I only did a quick round of the card battle in the digital version.
2. More interactions between players: One of the feedback that I got after the physical prototype said that I should take advantage of the fact that this is a two player game so I changed the main gameplay. I made it so the battles were between the 2 players instead of npcs.
3. Set up of board: I changed it from horizontal to vertical, made the tiles into circles, and made it more straightforward. This made more sense to me in the digital prototype. 
4. Cut for time but still to be included in the future: Relationship tiles where you answer characters questions right for battle buffs. Fishing spots where you collect as many fish as possible in a time limit.
5. Completely cut out: Different game modes. I think this distracts too much from the main game and would be too much work even outside of the class. 
6. Play as a ship instead individual characters: I changed the game loop from each of the 6 characters taking turns to each team taking turns, this makes it less tedious for players to move around the board. It also makes battles more fast-paced. I realized in the physical prototype that this took way too long and was not fun.
7. Not sure about defense cards: I didn't include them in the demo and am considering removing them alltogether but I would like to find a replacement eventually, maybe magic?
8. Card Battle Scores: In the demo I made it so instead of reducing the health of an enemy the goal is to true and get the highest score possible. I think in the future I go back to making it about defeating the enemy.
   
---

## Demo
https://lualikes.itch.io/attack-of-the-vampires-demo-it265
---

## Title
Attack of the Vampirates! 
---

## Concept Statement
- A spooky-themed board game where every choice matters, from where you travel to on a board to which characters you talk to, and card battles that balance luck with strategy.

---
## Genre and Style

### Genre
Multiplayer Card Battling Strategy Game
Subgenres: Narrative-focused, action, dueling card game

### Style
- A silly and spooky tale of pirates and vampires told through dark colors and detailed pixel art.
- Detailed character art with a focus on purple and red tones.
- Strategic gameplay where choices matter.
- Smooth UI and attention-getting visuals.
---

## Target Audience

### Demographics
- Target Audience: Casual gamers, horror fans, more dedicated gamers, fans of narrative-driven strategy, tabletop gamers
- Ages: appropriate for ages 13+, target age will be teens to young adults. 
### Accessibility
- Later on in the digital prototype if I keep working on this, I will implement a colorblind mode and a spanish language mode.
- Different gameplay modes at varying levels of difficulty
 

### Inclusivity Strategies
The main characters are a diverse crew of pirates which means players can have a fun time choosing who to play as. 
Increased complexity can be toggled on and off

---

## Core Gameplay Mechanics

### Primary Mechanics
Building relationships: As you go through the board, if you land on character tiles you will interact with different people who could help or hurt you. If you continuously talk to the same people, gift them fish, or answer their questions correctly, they will give you a variety of buffs. Some buffs include: faster move speed, reduced damage in vampire attacks, luckier fishing attempts, etc.

Fishing: In the digital game you would fish by casting your rod and reeling at the right time. In the physical game, you will throw your character and try to make it land on a fish.

Traversing through the map: Each character goes through the board by a die roll and lands on different spaces that offer benefits/damage. Special characters might move faster than others.

Vampire battles: If you land on the same space as an enemy, a turn-based fight will start. In the digital game, it's also possible for an attack to randomly occur if you don't land on an attack space. Each character has ~~1 special card unique to them and~~ 6 normal cards dealt ~~based on their type, (magic, support, and fighter).~~ The first character goes and must discard ~~3~~ 4 cards ~~(not including the special card)~~ without knowing what cards will come next ~~other characters have~~. The next ~~character~~ turn goes and does the same thing. After all 3 turns~~characters~~ discard ~~3~~ 4 cards each, only those that remain in hand will be played. Cards will either be attack, defend, or heal points, with different combos possible based on matching types or numbers on the cards.

### Goals and Challenges
The primary goal is to survive until the end of the voyage and get to the end of the board before the other player with as many of your crew still human as possible.
Subgoals include collecting fish and building relationships with characters.
~~In the Holy game mode, you will automatically lose if one of your crew is turned into a vampire.~~
~~In the Eternal Corruption game mode, your goal will be to gain the vampires favor and try to turn all your human crew into vampires. The challenges players encounter include enemy encounters and battles, terrain traversal, and balancing speed with safety.~~

### Progression

As you talk to more of the same characters, you can receive gifts that will help you in battle. 
The farther you move on the board, the more difficult the battles will become. 
Travelling across the board should take you 30min. 

### Game Rules
- Each player chooses a team, blue or green, and takes the character pieces associated with that team. Take the special card that goes with each character as well. 
- Take turns rolling the die and moving that many spaces, the shorter player has the first turn. 
- If you land on a fish space, throw a net at them, trying to get as many in as possible.
- If you land on an enemy space, you will have to duel the other player, go to the duel section to proceed.
- If one of your characters lands on the same space as a character from the other team, each player draws a card from the main deck, whoever gets the card with the lower number will have to give one fish (or the amount on the card) away to the other player.
- The game ends when all of a team’s characters reach the end of the board. Each team will then get points based on the amount of their characters that are still human, the amount of fish they caught, friends they made, and how fast they reached the end. 
Battle Rules: 
- The first character goes and must discard ~~3~~ 4 cards (not including the special card) without knowing what cards other characters have. 
- The next character goes and does the same thing. 
- After all 3 characters discard ~~3~~4 cards each, only those that remain in hand will be played. 
- Cards will either be attack, defend, or heal points, with different combos possible based on matching types or numbers on the cards.
- The battle ends if one character on either your team or the enemies loses all health points and dies. 

---

## Story and Setting

### Setting
This game takes place on a huge ornate pirate ship venturing through a dark and dangerous ocean. 
A terrible storm is brewing so it's cloudy and lightning is abundant. 
Throughout the ocean are tiny islands and caverns that the pirates can stop by, but vampires might be hiding within.
### Plot

The game follows 2 crews of pirates who must sail the seven seas to deliver rare fish. They stayed up too late one night partying and ended up behind the sailing schedule, so they are forced to take the riskier route, one that no man has gone through and lived to tell the tale. It's rumored that there are vampire sightings in the area, so the two crews, each with a unique cast of characters, must try to brave the route with as many of their members unchanged as possible
What is the player’s role in the story, and what major events drive the gameplay forward? 


### Characters
- First Crew:
- Celia: This stoic captain is banned in 22 territories. Where she goes, legend follows, what secrets is she hiding?
- Ambrose: An eccentric bartender with a selection of brews that can be used to hurt an enemy or help a friend.
- Jelly: A sea monster who broke into your ship and stayed there. Turns out they're a pretty chill guy but they go crazy in battle.
- Second Crew:
- Lord Frederick: This disgraced noble brought his holy books with him to cast spells on the seas.
- Walker: A former hunter and explorer with the best shot in the business and a love for grappling hooks. She also gardens on the side.
- Maria: A known thief with a hoarding problem. Rumor has it she's hiding her expensive weapon collection somewhere on the ship. Don't tell Lord Frederick that most of her loot comes straight from the royal treasury.

---
## Unique Selling Points (USP)
Novel combination of building character relationships and fighting card battles.
~~Multiple gameplay modes that attract different audiences.~~
Distinctive blend of both vampire and pirate themes in story and overall look and feel.
Detailed unique characters in a multiplayer format. 

---

## Inspiration

### Sources
- Books: Dracula by Bram Stoker
- Movies: Pirates Band of Misfits!
- Games: Hades, War

### Why It Matters
- Some of the story elements and aesthetics of vampires and pirates come from the first two sources. This helped me come up with character designs.
- The detailed style and colors of Hades inspired my choices. 


---

## Player Experience Goals
- Constant engagement: Feeling like every action matters should keep the player involved at all times.
- Humor and excitement: The characters and jokes should make for a fun experience.
- Suspense: The balance of mechanics and different ways to win should build tension.
- Rewarding battles: The decisions in battle should led to a satisfying win.  

---

## Technical Requirements

### Platform
- PC
- Possibly mobile in the future

### Tools
~~- Digital Prototype: Godot and Tabletopia~~
- Digital Prototype: GameMaker Studio 2
- Art: Aseprite ~~and Procreate~~
- Sound: freesound.org

---

## Art and Sound Direction

### Visual Style
- Hand Drawn 2D pixel art of each character, eventually with smooth animations.
- Focusing on deep reds and shades of purple, along with respective complementary colors.
- Detailed lineart and shading with more purple tones.
- Minimal UI elements, but each keeping with a pirate theme.

### Sound Design (I did not get to do sound but I would want to keep these themes)
- Spooky music to build atmosphere and tension
- Water/splash sound effects for fishing minigame
- Subtle menu and card sound effects to increase immersion
- Sword and spell sounds during card battles

---

## Monetization Strategy
- One time purchase digitally 
- Small DLCs with new stories/characters
---

## Treatment Details

### Gameplay Example

~~- Player 1 rolls 3 dice, 1 for each of their characters, and moves each based on that amount.~~
~~- Player 1 lands on a fishing space so they try to throw a net to capture as many fish as possible.~~
~~- Player 2 rolls 3 dice and moves each character based on that amount.~~
- Player 1 rolls a die and can land on one of 6 spaces.
- Player 2 rolls a die and can land on one of 6 spaces separate from Player 1.
- Player 2 lands on an attack space, so a battle is initiated.
- Player 1 draws ~~3~~ 6 cards, discards 4~~2~~. They pick one card to put in the play area. They pick another to hold till the next draw.  ~~And repeats this process for each of their characters.~~
- In the next draw, you can either choose the card you saved to go in the play area, save it for the final draw, or discard it.
- In the final draw, discard 5 cards and the last one will go in your play area. 
- When all characters on Player 1’s team have their remaining cards, these will do damage to Player 2 based on their color and number. Then it’s Player 2’s turn.
- This will repeat until 1 character on either team dies.
---

### Challenges and Considerations

#### Potential Risks
- Player Confusion: I think I need to write the rules more clearly.
- Overwhelming the player: There might be too many modes and I might need to narrow it down.
- Player Boredom: I need to test it more to make sure it’s fun.

#### Feasibility
- Time: I don’t think I have enough time this semester to get a lot done, but hopefully I manage time well.
- Skill: A big barrier is that I’m not great at coding so I don’t know how much I’ll be able to accomplish. I’ll try to watch tutorials. 
- Feasibility of small prototype: I think I can get a simple enough prototype done by the end of this class.

---

## Visualizing the Game Concept

### Concept Sketches or Storyboards

---

## Pitch Preparation

### Pitch Summary
"Attack of the Vampirates!" incorporates character-driven gameplay and fast paced card battles for a chaotically spooky board game experience. Mini games, randomness, ~~and 3 gameplay modes~~ create endless fun through a different adventure every round. With its blend of horror and humor, this strategic board game can fulfill a niche audience whilst attracting all types of players through its user-friendly rules and unique visuals.

### Target Audience Appeal
- Horror fans will appreciate the art, themes, and story.
- Casual gamers will enjoy the shorter and simpler game modes that they can pick up easily whenever they want.
Hardcore gamers will like the depth and strategic decision making that comes with mastering the game.

### Market Differentiation
- Different from most card games, Attack of the Vampirates! is narrative focused and incorporates character relationships into the gameplay. 
- Though many story-based games exist, none feature both a card and board game element.
- While card battles, fishing minigames, and character relationships exist in other games, none have combined all three. 
---

## External Feedback

### Feedback 1
- **Reviewer**:  
 M - my sister (in target demographic age 15, hardcore gamer)
- **Summary**:  
 They liked the story and thought the characters were very interesting. She really liked the vibe and theme of the game. She wants to know more information on the card battle, like how luck would work. Talking with her helped me get it to where it is now, but there's still more work to do
- **Refinement**:  
I need to flesh out the battles a lot more and actually test one out to see how exactly the attacks and defenses would work.
 
### Feedback 2
- **Reviewer**:  
Jessica - My Mom (Age 51, plays casual and puzzle games)
- **Summary**:  
She said everything was very vivid and felt like a real game. She thought that the fishing game mechanic didn't really fit with the vampire/pirate theme and said it would make more sense if there was treasure involved. The characters were her favorite part but she said she didn't know whether the third title "They're Biting Today, Son!" was a better fit for the game.
- **Refinement**:  
This helps me figure out where I need to edit the story and aesthetic elements to make this more cohesive and consistent, in order to not break immersion.

### Feedback 3
- **Reviewer**:  
Sebastian Vargas - (My friend/Vice President of NJIT's Game Development Club, Age 20, in target demographic)
- **Summary**:  
He immediately really liked the concept art and thought that character design was "incredible". His main critique was that he doesn't think the game takes advantage of being 2 player enough. He thinks there should be more opportunities for the two players to either work together or sabotage each other. Sebastian was also a little confused on the gameplay loop and wanted more information on the end goals and winning conditions.
- **Refinement**:  
I agree with his criticisms and will test out different winning/end conditions going forward to find a clearer, fun goal for the game. I will also work on ways for the two players to compete more to increase tension. I will also try to be clearer in my descriptions.

---

## Appendix
-I’m thinking of making the board more detailed and fleshing out the ocean environment and adding more islands/caves/fishing spots.
-I only got to finish a basic version of the card game but I would want to work on it more in the future. I might move it to a different engine because I had many issues in GameMaker.

---
