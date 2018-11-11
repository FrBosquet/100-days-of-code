# #100DaysOfCode Log - Round 1 - Fran Bosquet

The log of my #100DaysOfCode challenge. Started on [September 24, Monday, 2018].

## Log

### R1D1 
I worked among the icon system in my future blog app.
https://github.com/FrBosquet/franpress/commit/6bd931115b33408d42fbc0fc0a335ee4186886a1

### R1D2
I finalished my navigation header and started working on the option box for my posts.

### R1D3
I finished with the icon system and now all the icons works properly. I messed up a bit with the svg, so it deserves a future refactor. Pretty happy about it anyway.

### R1D4
Today i woke up earlier to complete my daily commitment. I added the copy of the page and the noisy bg, so the page is completed. Also, tweaked the shadows to make it feel more natural and added a drow shadow over the bg image.
https://github.com/FrBosquet/franpress/commit/c142469c2319a662eef335ab28893280c47aaf58

### R1D5
I introduced a darkmode to the header and improved my linter configuration. The rest of the time i worked on my blog post entry about this mockup phase.
https://github.com/FrBosquet/franpress/commit/a6347363ea7dbb14f5f95c718cf61cfe824f7f1d

### R1D6
Today i begun to provide mock data to my components using recompose to build hocs.
https://github.com/FrBosquet/franpress/commits/chapter-4

### R1D7
I implemented a crappy JSON format to describe a post content and its formating, and a first parser. Much to work and extend here, but it does work as long as you dont nest strongs inside ems or any other combination.

### R1D8
I added three more content types to the body of my posts: Images, subtitles and list. I also worked on revamping my yesterday algorithm to go from text to nodes to be able to next strongs, ems and a tags, but sadly it didnt work. Ill try again tomorrow
https://github.com/FrBosquet/franpress/commit/0808a7ab441d8c40f315573bbeb62b061380f203

### R1D9
I commited nothing today. I worked in an algorithm in Repl.it

### R1D10
Today i worked in the text parser implementing a test suite using jest
https://github.com/FrBosquet/franpress/commit/16ff0503adb41728e2c55816018f8a0ba25aa072

### R1D11
Second day using tdd to implement a text parsing algorithm. Very fun to do and a lot of progress, im near success for the custom text parsing.
https://github.com/FrBosquet/franpress/commit/83371801093b1776e8c19f69de6b3ccd49431899

### R1D12
I woke up early to work on my text parsing algorithm and finally ITS DONE. This has been tought, but using tdd and jest has made everything easier. Good lesson i got there. Now i will move forward and render some components using that output.
https://github.com/FrBosquet/franpress/commit/6536c06cb7c6259b29eb9ade598dd2a6024d82da

### R1D13
Today i cleaned the text parser and added asset injection for the link urls. Also, i implemented the react rendering of the generated nodes. Very good day so far.
https://github.com/FrBosquet/franpress/commit/ca9d39149926b032ce2ba6199a17ccf560eeae04

### R1D14
Today i used and event listener to get the scroll height in my page and update the section selected and the header color
https://github.com/FrBosquet/franpress/commit/a6a7aa76795b876fd37f9d77eeaa2c02aa7eb96c
R1D2
### R1D15
Today i spent some time writing what i have done to build the blog mock components in my current blog

### R1D16
Today i finished the blogpost about the component mocking in my blog project and its online in www.franbosquet.com

### R1D17
I added an apollo graphql server and started working on the post type. Tomorrow ill try to connect the client to retrieve data from this server.
https://github.com/FrBosquet/franpress/commit/0fc9b8b6e7379b34d6df51baf66c9f4ff04f6cdb

### R1D18
I connected my app to my apollo server and now all the rendered data is coming from there, no more mock data. Also i make the navigation items depends of the entry content (the where mocked too) and make some cosmetic changes.
https://github.com/FrBosquet/franpress/commit/098885d4b428df2b714d3051b60a4d39970fe428

### FREE DAY - 13 OCT 18
I go for a walk in the guadarrama mountains and spent the day with friends

### R1D19
Today i started the implementation of a local state in apollo. I found the docs pretty confusing and im not happy how is working, but i have my first local query working. Hope its get better with practice
https://github.com/FrBosquet/franpress/commit/b9911a5ca05ab3465b21f490b0494676ec7089de

### R1D20
I used the local state to decide wich post i have to query from apollo
https://github.com/FrBosquet/franpress/commit/914b292e8aba7aca5820bf474fe7730cb897974a

### R1D21
I used a mutation to change the local state
https://github.com/FrBosquet/franpress/commit/28e6701df188d4e80e0f4dd6500bf4c1451344f5

### R1D22
I implemented the post navigation so i can go to next and prev post. Also, i disabled the next/prev button qhen in the last or first post.
https://github.com/FrBosquet/franpress/commit/ad6254b48e7508c1e518207743b38605531c2b00

### R1D23
Today i created a trello board to organize my work and writed down some paragraphs in the blog about last week work. Not actually code, but for me its part of my code project so... code :D

### R1D24
I added storybook to my project and worked on an animated icon which is going to work as a spinner.
https://github.com/FrBosquet/franpress/commit/ebe1efe8b85f254ce5066006ad323b7bdbe00295

### R1D25
I improved the "spinner" icon, added an animated fade screen and pushed all of that to the main view so its show while apollo is loading

### R1D26
I added a custom background, icon and date for each post. Now post are ordered cronologically by a timestamp, so the nextProp and prevPost are calculated dinamically.
https://github.com/FrBosquet/franpress/commit/9a478da0023b6f6fb63ebe79ff2bb92b1d815cc4

### R1D27
I studied about tensorflow and machinelearning. I wrote in the blog

### R1D28
Today i get more into tensorflow and developed a very primitive line predictor. Also, i published a tecnical article in the blog.
https://codepen.io/FrBosquet/pen/wYEmad

### R1D29
I solved some katas at codewars.com, i did some tutorials on tensorflowjs and implemented a database for my blog and the consequent mutators in graphql to handle it. No more mocked data in json
https://github.com/FrBosquet/franpress/commit/3cf12da37daa94d572238db401b2dd5dc6da9f3f

### R1D30
I designed a component to host my list of posts and begun to implement it as a React component. Also I blown my mind comnpletely by completing the "Maker of things" kata in codewars, a crazy one abot JS metaprograming.
https://github.com/FrBosquet/franpress/commit/6500f555b9e573413bc47184f1a8e740eeb83eae

### R1D31
Solved a kata and worked with D Torrijos in a new React 360 project

### R1D32
Worked with A Chacón in our new react turn based RPG
https://github.com/AdrianChacon/FightToDeath/commit/3e392ea8b9de40ffb8ff3218b8c2904ef033a226

### R1D33
Played with React 360
https://github.com/FrBosquet/r360-playground/commit/2c2b7f79794ac8a99a354b3c41e2581a4d95b631

### R1D34
Im working in a vanilla canvas beerpong game
https://github.com/FrBosquet/beerpong-canvas/commit/f5cce446e5d43c233b0bcf27f7fae5ea272c2fac

### R1D35
I completed the basic functionality for the beerpong game
https://github.com/FrBosquet/beerpong-canvas/commit/2d00e11ec2556ac973605ee53b3412823c02cbe4

### R1D36
Refactoring my canvas beer pong so I can reuse the game logic in React 360
https://github.com/FrBosquet/beerpong-canvas/commit/2106e9b755f02124da6888ab9435102c635f33ab

### R1D37
Worked in the stylebook of Fight To Death and abstracted some component structures in complex components
https://github.com/AdrianChacon/FightToDeath/commit/9d64f43a7f6a2497076c7097cc301001c7b3041b

### FREE DAY - 2 NOV 18
Get out on a short vacation to Bocigas de Perales with friends. No time to code today.

### R1D38
Started to design the fighter spec for the core game system using jest and tdd
https://github.com/AdrianChacon/FightToDeath/commit/7037847dfe9686a8705626e391e827e1500f71e0

### R1D39
Continued developing features for the core game system of Fight to death
using jest and tdd
https://github.com/AdrianChacon/FightToDeath/commit/53c9e204ed56f324354f283ff324ba8c632358e7

### R1D40
More features on the fighter class for the FightToDeath core fighting system. So much fun and advancing at good pace, passed 50% of the things i want it to have before passing to the next class (probably party)
https://github.com/AdrianChacon/FightToDeath/commit/c9d33a2fe808afb0f486e3e1f32be366068ff430

### R1D41
Worked with @pastoruk in our login for fight to death. Also added more functionality to the fighter class, which is almost complete. Very nice and productive day
https://github.com/AdrianChacon/FightToDeath/commit/44d87eea4459455065bab2c76dde4b9245a77e65

### R1D42
Added stackable effects to the fighter
https://github.com/AdrianChacon/FightToDeath/commit/485769e0eb08f139bbabb5a0456bdb66b1cf5899

### R1D43
I completed this kata in codewars https://www.codewars.com/kata/assembler-interpreter-part-ii/javascript

### R1D44
Worked in VeeRPong with David, trying to figure out how it works. Also, completed more tasks in FightToDeath.

### R1D45
Advanced more into fighter definition for our RPG FightToDeath (provisional name) adding skills and perks
https://github.com/AdrianChacon/FightToDeath/commit/0b50a31ba74161557ac5006a2e171f66843fcde5

### R1D46
Added the turn logic to the fighter class. Only thing left is to add some triggers and some random tests and its done.
https://github.com/AdrianChacon/FightToDeath/commit/6d3b68a65d7f758773845811e6932c742ad4f53f