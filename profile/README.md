<div align=center>

<img src="https://avatars.githubusercontent.com/u/100030939?s=400&u=808a96ffa048f92350d284580d4f79c98e7af505&v=4" width="400" height="400" alt="logo">

# Uni-verse

**Your music is our dark matter!**

Uni-verse is an audio streaming platforms made for the creators.

</div>

We are taking creator oriented audio streaming platforms to the next level with several features:

- Audio sample based search
- Plagiat detection
- Collaboration
- Resource sharing for music production \*
- Privante instantaneous messaging
- An Android app for listening
- **MAYBE ONE DAY** direct daw integration through VST

This Organisation holds the code that allows the uni-verse plarform to run.

Uni-verse is initially a school project and is actively being turned into a PoC and a personnal project.
It's not production ready and nor is it simply ready at all.

Check out how it is built in [the wiki](https://uni-verse-fm.github.io).


<br/>

# Current state (WIP):

Currently the whole app is not functional, it has deprecated dependencies, a bit of tech debt, and I do not have a kubernetes cluster anymore.

Especially, for NPM dependencies reasons, the frontend has to be re-written.

Current Todo list includes roughly :

- [ ] Translating the documentation in english

  - [x] Backend
  - [x] Frontend
  - [ ] Android
  - [ ] FP
  - [ ] Automations

- [x] [Organising the documentation in some separate web page via Hugo](https://uni-verse-fm.github.io)

- [x] [Creating a development environment with infra](https://github.com/uni-verse-fm/uni-verse-dev):

  - [x] RabbitMQ
  - [x] MongoDB
  - [x] Minio
  - [x] Elastic Search
  - [x] Frontend (curently being rewriten)
  - [ ] ~~FP workers~~

- [x] [Setup some production environment](https://uni-verse.vagahbond.com):

  - [x] RabbitMQ
  - [x] MongoDB
  - [x] Minio
  - [x] Elastic Search
  - [ ] ~~FP workers~~(Not needed until the frontend is re-written)
  - [x] Frontend (ongoing rewrite)

- [ ] Frontend
  - [ ] Svelte re-write every interface

<br/>

# Members

- [Vagahbond](https://github.com/vagahbond)
- [Abdelilah](https://github.com/abdelillah-tech)
