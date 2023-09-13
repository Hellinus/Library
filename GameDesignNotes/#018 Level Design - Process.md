# #018 Level Design - Process
From [The Level Design Book](https://book.leveldesignbook.com/).
[TOC]

## prologue: What is level design
### What is a level
A level is a space where a game happens. Some examples:
- the Fortnite island, an obstacle course ("obby") in Roblox
- a basketball court, race track, or playground
- a Monopoly board, crossword puzzle, coloring book

All these game spaces set **boundaries** for players to move and interact.
Different levels offer **variation**. For example all basketball courts have similar shapes, but an outdoor court and an indoor gym offer different **experiences, cultures, and moods.**
Level designers focus on how different game spaces can make players **feel** and **behave.**

### What is level design
Level design is the practice of planning and building spaces for video games...
... usually first-person or third-person action shooters.

#### Functional level design vs. environment art
**Level designers** focus on shaping player behavior. In large studios, they often write documentation, draft layouts, build blockouts, observe playtests, and balance maps and encounters.

In contrast, an **environment artist** focuses more on graphics. They art pass models, materials, set dressing, and lighting to refine the level's visual appearance. While this is mostly decoration, good environment art supports experience design goals and helps players play.

- Formal industrial sense of capital-L capital-D "Level Design" without environment art
- Broad common sense "level design" includes environment art / anything in a level

#### Room design vs. world design
Level designers can spend days or even weeks designing a single room.

But for a huge battle royale, open world, or MMO with hundreds / thousands of rooms, agonizing over a single room is impractical. A world designer considers flow and wayfinding for neighborhoods instead of houses, biomes instead of places, categories instead of instances. This generic approach lets players and systems breathe. But without players or systems to fill that void, the resulting world may feel empty or bland.

#### Theory vs. "go map"
The only way to become a level designer... is to make levels. Ideally, a lot of levels.

### Zooming out
Although level designers should focus on player behavior, sometimes we must zoom out and see the big picture.

A level is a combination of spatial design, art, psychology, programming, and culture. From the player's perspective, there is no difference between level design and environment art. Anything that affects the game world is level design.

Avoid the lure of simplistic dos-and-don'ts. Levels are more than collections of rooms and cover boxes, and more than landscapes with rocks and trees sprinkled on top. A level possesses history and culture and intent, and as responsible designers we must consider the entire play experience.

## How to make a level
Most 3D level design projects involve this process:
1. Pre-production: plan out the big ideas and overall experience design.
2. Combat (optional): for combat games, define how player(s) and enemy types interact.
3. Layout: sketch a visual top-down 2D plan for a level.
4. Blockout: build a basic in-game 3D rough draft and playtest it.
5. Scripting: integrate events and behaviors (missions, quests, doors, buttons, AI)
6. Lighting: arrange light sources for depth and readability
7. Environment Art: "art pass" the level with props and set dressing
8. Release: document, publicize, and publish the project.


### Tailor the process
Every level / project has different needs. There is no single foolproof way to make a level.
- Group projects need more pre-production and planning, like pacing outlines and layout drawings. Without enough communication and documentation, collaborators can't collaborate.
- Combat games / multiplayer maps need more blockout time to tune encounters and map balance with a strong focus on playtesting.
- Single player levels with a storytelling focus benefit less from a long blockout period. That may sound appealing but it's actually a special hell with zero certainty. When is a story "good enough"? You'll need a lot of iterations on scripting and environment art. If your story changes, you'll have to redo everything, and it's hard to keep everything in sync. Ever play a game where the story doesn't make sense? That's probably going to be your game too.

### Process overview
#### 1. Pre-production
Pre-production is about planning the basic shape and scope of the project. What is the project about? What are the design goals and constraints?

Beginners often neglect project planning entirely, while experienced designers sometimes over-plan. Big commercial studios often spend months or even years in pre-production. When collaborating in a group, this phase is very important because this is when you all align your expectations. When working solo as a hobbyist, you can probably get away with less planning.

Pre-production plans are usually text documents, boards with movable cards, and spreadsheets.

#### 2. Combat design (optional)
If your project is about combat, then what does a typical fight look like, what is a battle made of? How do players prepare? How can you make fights feel varied and fresh? 

Combat is like any other game system or mechanic. You should define these experience design goals before you make levels for them.

If you're making a combat game from scratch, the fights won't "feel good" until programmers and artists make it functional and readable. You basically have to make the whole game before you'll know what the combat feels like! Because it's so much work, we recommend modding combat games so you can practice on pre-built battle-tested systems.

#### 3. Layout
The layout is the basic structure of the level, usually a flat 2D drawing of core areas and elements. 

For a small solo hobby project, a simple layout sketch, even a scribble, can be enough.

For a group / big project, detailed layout drawings are important communication tools. No one can read your mind; if you don't visualize it and talk about it, then no one will know what you want. 

Layout drawings are usually top-down 2D floor plans, but isometric / perspective drawings are common too. Remember, this isn't about being a great artist; it's about communication! The drawing is a visual plan for where the player can go and what they can do. 

#### 4. Blockout
A blockout is a playable rough draft of the level, built with simple blocky 3D shapes in low detail. 

We prototype the basic structure of the level so we can playtest it within the game engine. Playtesting helps us decide whether the level is too small or too big, confusing or entertaining, balanced or broken, etc.

This playtesting is important for any combat game, or anything where rearranging a room can cause big changes in player behavior. If you realize a room design isn't working, then you can modify it more easily when it is made of simple shapes.

Blockout files are playable game levels / scene files loaded into the game engine.

#### 5. Scripting
Scripting is about integrating behaviors, events, and game logic into a level.

Door scripting is one of the most difficult problems in game development. Trains and moving platforms are even more complicated. It's better to start with buttons and collectibles.

Mission objectives, quests, cutscenes, choreography -- and any AI control / combat / encounter design -- often rely on scripting. If you're scared of coding, don't be afraid, many game engines and toolsets have special scripting languages and tools to simplify the programming process.

Level design culture tends to underappreciates scripters, yet scripting is what makes a level feel "alive" and is crucial for transforming a map into an experience.

#### 6. Lighting
Lighting adds shadow and depth to a blockout, helping players understand the core shape of the level. 

Without light, the 3D game world will feel more like a flat 2D image, and it will be difficult to gauge distances or understand the full layout. Light and shadow also serve as a form of cover / layer of information essential for combat gameplay.

While the game industry usually treats lighting more as a decorative facet of environment art, we argue that lighting has crucial gameplay functions and must be crafted in deep consultation with level designers.

#### 7. Environment Art
Once you have enough certainty about the overall shape and flow of the level, you can begin adding more environment art, or visual detail.

An art pass is the process of adding these details. Most projects will require multiple art passes.

Many people think art passing is the "fun part." Beginners often rush too quickly into art passing without adequate planning, layout, or blockout work. A premature art pass locks-in early design mistakes because it becomes "expensive" to change the level and thus redo all the artwork. So, resist the urge! Don't rush into an art pass!

#### 8. Release
When the project is complete, it is time to release and make sure it reaches your audience.

For commercial projects, the game launch is just the beginning of the nightmare -- you must continue to market and publicize the project, gauge user feedback, ship bug fixes, and even build out additional post-launch content. 

For personal portfolio projects, you must document the level design properly, or else no one will understand what you did. Without effective documentation, the project basically does not exist. 

Beginners often do not put enough time into the release phase, and assume the project will speak for itself -- but if no one knows about it, then your work has no one to speak to.

### To review
Level design usually involves multiple steps, in this general order: (1) pre-production, (2) combat design (unless it's not a combat game), (3) layout, (4) blockout, (5) scripting, (6) lighting, (7) environment art, and (8) release.

But every project is different. Sometimes you may want to skip a layout phase, or expand a scripting phase, or do environment art before scripting, etc. 

If you are early in a project or early your level design career, you should probably try doing everything until you figure out what process works best for you.

> *writing by Hellinus - 2023.9.13*
