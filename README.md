
# Alien Swarm++

Alien Swarm++ is a project aimed on porting multiple new features and games to the ASW engine branch.

## Features

- [X] Half-Life 2 support [(StanR)](https://github.com/stanriders/)
- [ ] Half-Life 2: Episodic support [(StanR)](https://github.com/stanriders/)
- [X] Swarm suport (VALVe)
- [X] Valve Project Creator support (VALVe)
- [ ] Counter-Strike: Source support [(Demez)](https://github.com/Demez/source-asw-sdk)
- [ ] TF2 Support [(Demez)](https://github.com/Demez/source-asw-sdk)
- [ ] Portal 1/2 support (DecalOverdose)
- [ ] Lua scripting
- [ ] Deferred Shading
- [ ] Physically Based Renderer
## FAQ

#### Do you plan on using leaked code for main code?

No, I might use leaked code in the repo (from 2012 leak), but only for game code, I wouldn't rely on it for everything. Major stuff that are impossible without leaked code, I could probably do with code hacks and reverse-engineering tools 

## Build the project

Clone the project

```bash
  git clone https://github.com/ASWPorts/ASW-PlusPlus
```

Go to the project directory

```bash
  cd ASW-PlusPlus/src
```

Run Valve Project Creator to create the solution:

Visual Studio 2010: 
```bash
creategameprojects2010.bat
```

Visual Studio 2012:
```bash
creategameprojects2012.bat
```

Visual Studio 2013:
```bash
creategameprojects2013.bat
```

Then compile using the same Visual Studio version!