# Welcome to the Workshop Tutorial series repository
In here you'll be able to find scripts, course material and other miscellanous useful things to better kickstart your workshop journey, don't forget to check out the series on [VVizard's channel](https://www.youtube.com/@VVizardWS)

## Here's a quick map of what you'll find here
Each individual lesson will have its own folder containing the breakdown of the tackled topics, a direct link to its YouTube Video and any specific course material that's shown and used so that it can be viewed by the students

```
├── Characters
    ├── Templates
    ├── Basic Tutorials
    ├── Intermediate Tutorials
    ├── Advanced Tutorials
    └── Design Tutorials
├── Stages
    ├── Templates
    ├── Basic Tutorials
    ├── Intermediate Tutorials
    ├── Advanced Tutorials
    └── Design Tutorials
├── Buddies
    ├── Templates
    ├── Basic Tutorials
    ├── Intermediate Tutorials
    ├── Advanced Tutorials
    └── Design Tutorials
├── Skins
    ├── Templates
    ├── Basic Tutorials
    ├── Intermediate Tutorials
    ├── Advanced Tutorials
    └── Design Tutorials
├── Misc Tutorials
└── Code Snippets
```

## Important guidelines
This tutorial series is to be regarded as **the** RoA Workshop gold standard, therefore all the information that's meant to be shared as **standard** has to be peer reviewed.
Information that is not considerable as a standard is still welcome, offering different perspectives to things is important, however such information has to be marked as such and has to include an explanation for what its pros and cons are relative to the accepted standard, for example:
The Dakurai grab system that uses PS_FLASHED, is not standard but it's worth teaching.

The same goes for any template material which has to be accompanied by a .txt file of the same name detailing any needed information.

Make sure to include the Author's name in the relative material if it's not standard, for example:
`Dakurai_Empty_Character_Template`


For any and all additions contact Dakurai or VVizard on Discord


## List of all the classes per category (might get removed)
Misc
- templates and code reusability, pros, cons, do's and don'ts

Characters specifically

Basics (ideally without major necessity of direct coding)
- How to get started (workshop folder, IDEs, creating the work environment)
- Character basics and setting up movement
- basic attacks, windows and hitboxes/projectiles
- roa colors.gml website and how to set up alt colors
- how to add character compatibilities to your character
- standard workshop code practices
- how to upload and publish your workshop item

Design
- character sprites, how to make a character look like it belongs
- how rivals designs movesets
- designing a moveset for rivals
- gamefeel and nuances
- sound effects and the base rivals library
- how to promote your rivals workshop character (trailers and publicity)
- trailers, what to show and how to show it best

Intermediate (stuff you see on average characters that requires code)
- rivals gml, language overview
- hit effects, Colormapping and other basic visual things
- what is an article (includes solid and plat info)
- setting up basic article behaviour (state machine)
- hitbox update and hitbox behaviour
- collisions and other interactions (and velocity shenanigans, including old speeds with hitpause)
- standard CSS visuals (name, base sprite etc)
- synced var and CSS interaction
- init shader and color shenanigans
- object depth and visuals layer handling
- basic character AI (Karu AI)
- make basic compatibilities for your character (sprites, text etc)
- how to make character skins, basic skin handler
- ways of making status effects (array method, other init method, other init with applier method)
- stage music override
- how to code an install
- how to code command grabs (dakurai method, the forced hitstun method, the old wrapped method)
- how to make custom hud graphics
- how to code a meter
- runes and how to use them
- dust FX and making custom dust


Advanced (the secret knowledge to crack rivals open)
- how to optimise your code
- basic gml objects, standard variables and how rivals does common behaviour
- hit effects, in depth object analysis (ft. dust effects and why they're awful)
- rivals particle system through hit effects
- articles, in depth object analysis
- persistent articles and advanced data storage through persistent articles
- articles for visuals
- advanced article structures (articles that attack alongside you, advanced articles control)
- oPlayers, in depth object analysis
- overriding basic player behaviour
- oPlayer clones and how to handle them from basic clone to advanced logic (stands as an example, with other potential things)
- exploiting article slots for infinite color slots
- CSS, in depth structure analysis and how to pretty up your character select screen
- advanced synced var handling and how to optimise around 32 bits of space
- respawn platform, in depth structure analysis and how to make a custom respawn
- win screen, in depth structure analysis and how to make a custom win screen
- advanced compatibility for your character (events handling and other custom behaviour)
- how to make or improve visual effects with code (primitives, blendmodes, masking, GPU fog, sprite manipulation)
- stance changing (pythra like or between different oplayer objects)
- how to make a 2d rig for coded animation (with ik and fk notions)
- handle outside logic in dittos (port priority based logic handling)
- room object, object overview and how to manipulate global room variables (room speed, room size etc)
- hitscans and advanced/optimised collision search algorithms (hitscans, binary search, double precision search)
- how to make a ground article (like etalus ice or sylv grass)
- rivals scripts, order and important logic


Stages specifically

Basics (ideally without major necessity of direct coding)
- How to get started (making a basic stage)
- making an advanced stage
- other stage creator functionalities

Design
- stage design basics (how to stage visuals, how to blastzones)
- gamefeel and nuances

Intermediate (stuff you see on average stages that requires code)
- how to code basic stage hazards (lava, projectiles, random hitboxes)
- adding more visuals to your stage (article draws)
- stage articles basics
- stage layering logic and nuances
- how to add compatibility to your stage
- how to code complex stage hazards (enemies, anything with slightly more complex logic)
- how to interact with the playing characters (with oPlayer stuff you can do, drawing sprites, lifting information in general and influencing oPlayers)
- custom stage solids and how to handle them
- messing with stage assets dynamically

Advanced (the secret knowledge to crack rivals open)
- stage object and stage oPlayer, in depth object analysis and breaking the limits of stage size
- stage npcs, in depth object analysis
- making custom camera logic for stages
- making slope colliders for stages
- how to code a stage boss
- how to code a custom end screen
- how to code a room system for your stage
- how to code a cutscene system for your stage


Buddies specifically

Basics (ideally without major necessity of direct coding)
- getting started with buddies and coding a basic buddy with just sprites

Intermediate (stuff you see on average characters that requires code)
- buddy code basics
- giving the buddy custom behaviour
- interacting with the owner
- buddy interaction with hitboxes
- how to code an assist through the assist template
- how to register player events (player Death, player hitting opponent, player taking damage etc)

Advanced (the secret knowledge to crack rivals open)
- pet object, in depth object analysis
- advanced hitbox interaction
- buddy collision interaction
- how to code a custom gamemode in a buddy

advanced basecast skins
- how to make an advanced skin
- possibilities of advanced skins
- messing around with advanced skins
- basecast oPlayers, an in depth analysis