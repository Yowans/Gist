
wilder@wilder-ThinkPad-T440p:~$ cd planets
wilder@wilder-ThinkPad-T440p:~/planets$ mkdir -p planets/real/fictional/inhabited
mkdir: impossible de créer le répertoire «planets»: N'est pas un dossier
wilder@wilder-ThinkPad-T440p:~/planets$ cd ..
wilder@wilder-ThinkPad-T440p:~$ git it
git : 'it' n'est pas une commande git. Voir 'git --help'.

La commande la plus ressemblante est
	init
wilder@wilder-ThinkPad-T440p:~$ git init
Dépôt Git vide initialisé dans /home/wilder/.git/
wilder@wilder-ThinkPad-T440p:~$ cd planets
wilder@wilder-ThinkPad-T440p:~/planets$ 
wilder@wilder-ThinkPad-T440p:~/planets$ mkdir real
wilder@wilder-ThinkPad-T440p:~/planets$ mkdir fictional
wilder@wilder-ThinkPad-T440p:~/planets$ mkdir inhabited
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ mkdir terrestrial
wilder@wilder-ThinkPad-T440p:~/planets/real$ mkdir gas-giants
wilder@wilder-ThinkPad-T440p:~/planets/real$ mkdir dwarf-planets
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp pluto.jpeg/real
cp: opérande de fichier cible manquant après 'pluto.jpeg/real'
Saisissez « cp --help » pour plus d'informations.
wilder@wilder-ThinkPad-T440p:~/planets$ cp pluto.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  real         venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     planets       saturn.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  pluto.jpeg    uranus.jpeg
dwarf-planets  gas-giants  pluto.jpeg  terrestrial
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp pluto.jpeg dwarf-planets
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls dwarf-planets
dwarf-planets  gas-giants  pluto.jpeg  terrestrial
pluto.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp arrakis fictional
cp: impossible d'évaluer 'arrakis': Aucun fichier ou dossier de ce type
wilder@wilder-ThinkPad-T440p:~/planets$ cp arrakis.jpeg fictional
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls fictional
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  real         venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     planets       saturn.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  pluto.jpeg    uranus.jpeg
arrakis.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp coruscant.jpeg fictional
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls fictional
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  real         venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     planets       saturn.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  pluto.jpeg    uranus.jpeg
arrakis.jpeg  coruscant.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cybertron.jpeg fictional
cybertron.jpeg : commande introuvable
wilder@wilder-ThinkPad-T440p:~/planets$ cp cybertron.jpeg fictional
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls fictional
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  real         venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     planets       saturn.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  pluto.jpeg    uranus.jpeg
arrakis.jpeg  coruscant.jpeg  cybertron.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp earth.jpeg terrestrial
wilder@wilder-ThinkPad-T440p:~/planets$ cp earth.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp earth.jpeg terrestrial
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls terrestrial
dwarf-planets  earth.jpeg  gas-giants  pluto.jpeg  terrestrial
earth.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp jupiter.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp jupiter.jpeg gas-giants
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls gas-giants
dwarf-planets  earth.jpeg  gas-giants  jupiter.jpeg  pluto.jpeg  terrestrial
jupiter.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp mars.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  real         venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     planets       saturn.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  pluto.jpeg    uranus.jpeg
dwarf-planets  gas-giants    mars.jpeg   terrestrial
earth.jpeg     jupiter.jpeg  pluto.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp mars.jpeg gas-giants
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls gas-giants
dwarf-planets  gas-giants    mars.jpeg   terrestrial
earth.jpeg     jupiter.jpeg  pluto.jpeg
jupiter.jpeg  mars.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp mercury.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  real         venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     planets       saturn.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  pluto.jpeg    uranus.jpeg
dwarf-planets  gas-giants    mars.jpeg     pluto.jpeg
earth.jpeg     jupiter.jpeg  mercury.jpeg  terrestrial
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp mercury.jpeg gas-giants
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls gas-giants
dwarf-planets  gas-giants    mars.jpeg     pluto.jpeg
earth.jpeg     jupiter.jpeg  mercury.jpeg  terrestrial
jupiter.jpeg  mars.jpeg  mercury.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp neptune.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    uranus.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  real          venus.jpeg
dwarf-planets  gas-giants    mars.jpeg     neptune.jpeg  terrestrial
earth.jpeg     jupiter.jpeg  mercury.jpeg  pluto.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp neptune.jpeg gas-giants
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls gas-giants
dwarf-planets  gas-giants    mars.jpeg     neptune.jpeg  terrestrial
earth.jpeg     jupiter.jpeg  mercury.jpeg  pluto.jpeg
jupiter.jpeg  mars.jpeg  mercury.jpeg  neptune.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp saturn.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    uranus.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  real          venus.jpeg
dwarf-planets  gas-giants    mars.jpeg     neptune.jpeg  saturn.jpeg
earth.jpeg     jupiter.jpeg  mercury.jpeg  pluto.jpeg    terrestrial
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp saturn.jpeg gas-giants
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls gas-giants
dwarf-planets  gas-giants    mars.jpeg     neptune.jpeg  saturn.jpeg
earth.jpeg     jupiter.jpeg  mercury.jpeg  pluto.jpeg    terrestrial
jupiter.jpeg  mars.jpeg  mercury.jpeg  neptune.jpeg  saturn.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp uranus.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    uranus.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  real          venus.jpeg
dwarf-planets  jupiter.jpeg  neptune.jpeg  terrestrial
earth.jpeg     mars.jpeg     pluto.jpeg    uranus.jpeg
gas-giants     mercury.jpeg  saturn.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp uranus.jpeg terrestrial
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls terrestrial
dwarf-planets  jupiter.jpeg  neptune.jpeg  terrestrial
earth.jpeg     mars.jpeg     pluto.jpeg    uranus.jpeg
gas-giants     mercury.jpeg  saturn.jpeg
earth.jpeg  uranus.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp venus.jpeg real
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls real
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    uranus.jpeg
cybertron.jpeg  inhabited   mercury.jpeg  real          venus.jpeg
dwarf-planets  jupiter.jpeg  neptune.jpeg  terrestrial
earth.jpeg     mars.jpeg     pluto.jpeg    uranus.jpeg
gas-giants     mercury.jpeg  saturn.jpeg   venus.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp venus.jpeg terrestrial
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls terrestrial
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg  venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    terrestrial
cybertron.jpeg  inhabited   mercury.jpeg  real          uranus.jpeg
terrestrial
wilder@wilder-ThinkPad-T440p:~/planets$ cd terrestrial
bash: cd: terrestrial: N'est pas un dossier
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cp venus.jpeg terrestrial
wilder@wilder-ThinkPad-T440p:~/planets/real$ ls ; ls terrestrial
dwarf-planets  jupiter.jpeg  neptune.jpeg  terrestrial
earth.jpeg     mars.jpeg     pluto.jpeg    uranus.jpeg
gas-giants     mercury.jpeg  saturn.jpeg   venus.jpeg
earth.jpeg  uranus.jpeg  venus.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cp arrakis.jpeg inhabited
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls inhabited
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg  venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    terrestrial
cybertron.jpeg  inhabited   mercury.jpeg  real          uranus.jpeg
arrakis.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp coruscant.jpeg inhabited
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls inhabited
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg  venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    terrestrial
cybertron.jpeg  inhabited   mercury.jpeg  real          uranus.jpeg
arrakis.jpeg  coruscant.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp cybertron.jpeg inhabited
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls inhabited
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg  venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    terrestrial
cybertron.jpeg  inhabited   mercury.jpeg  real          uranus.jpeg
arrakis.jpeg  coruscant.jpeg  cybertron.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp earth.jpeg inhabited
wilder@wilder-ThinkPad-T440p:~/planets$ ls ; ls inhabited
arrakis.jpeg    earth.jpeg  jupiter.jpeg  neptune.jpeg  saturn.jpeg  venus.jpeg
coruscant.jpeg  fictional   mars.jpeg     pluto.jpeg    terrestrial
cybertron.jpeg  inhabited   mercury.jpeg  real          uranus.jpeg
arrakis.jpeg  coruscant.jpeg  cybertron.jpeg  earth.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd dwarf-planets
wilder@wilder-ThinkPad-T440p:~/planets/real/dwarf-planets$ rm pluto.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real/dwarf-planets$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets/real$ rm pluto.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ rm pluto.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ find
.
./fictional
./fictional/cybertron.jpeg
./fictional/coruscant.jpeg
./fictional/arrakis.jpeg
./cybertron.jpeg
./uranus.jpeg
./mercury.jpeg
./venus.jpeg
./mars.jpeg
./terrestrial
./earth.jpeg
./saturn.jpeg
./inhabited
./inhabited/cybertron.jpeg
./inhabited/earth.jpeg
./inhabited/coruscant.jpeg
./inhabited/arrakis.jpeg
./neptune.jpeg
./real
./real/uranus.jpeg
./real/mercury.jpeg
./real/venus.jpeg
./real/mars.jpeg
./real/dwarf-planets
./real/gas-giants
./real/gas-giants/mercury.jpeg
./real/gas-giants/mars.jpeg
./real/gas-giants/saturn.jpeg
./real/gas-giants/neptune.jpeg
./real/gas-giants/jupiter.jpeg
./real/terrestrial
./real/terrestrial/uranus.jpeg
./real/terrestrial/venus.jpeg
./real/terrestrial/earth.jpeg
./real/earth.jpeg
./real/saturn.jpeg
./real/neptune.jpeg
./real/jupiter.jpeg
./coruscant.jpeg
./arrakis.jpeg
./jupiter.jpeg
wilder@wilder-ThinkPad-T440p:~/planets$ cp real
cp: opérande de fichier cible manquant après 'real'
Saisissez « cp --help » pour plus d'informations.
wilder@wilder-ThinkPad-T440p:~/planets$ cd real
wilder@wilder-ThinkPad-T440p:~/planets/real$ find
.
./uranus.jpeg
./mercury.jpeg
./venus.jpeg
./mars.jpeg
./dwarf-planets
./gas-giants
./gas-giants/mercury.jpeg
./gas-giants/mars.jpeg
./gas-giants/saturn.jpeg
./gas-giants/neptune.jpeg
./gas-giants/jupiter.jpeg
./terrestrial
./terrestrial/uranus.jpeg
./terrestrial/venus.jpeg
./terrestrial/earth.jpeg
./earth.jpeg
./saturn.jpeg
./neptune.jpeg
./jupiter.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/real$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cd inhabited
wilder@wilder-ThinkPad-T440p:~/planets/inhabited$ find
.
./cybertron.jpeg
./earth.jpeg
./coruscant.jpeg
./arrakis.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/inhabited$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ cd fictional
wilder@wilder-ThinkPad-T440p:~/planets/fictional$ find
.
./cybertron.jpeg
./coruscant.jpeg
./arrakis.jpeg
wilder@wilder-ThinkPad-T440p:~/planets/fictional$ cd ..
wilder@wilder-ThinkPad-T440p:~/planets$ 
