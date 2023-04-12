# UD-Demo-IMU-Vallee-Du-Gier-Mockup
Demo [UD-Viz](https://github.com/VCityTeam/UD-Viz#readme) pour le développement d'une maquette Lego sur le territoire Rive de Gier pour le festival [popSciences](https://popsciences.universite-lyon.fr/) du 13/14 mai 2023.
[IMU](https://imu.universite-lyon.fr/) aura un stand lors de ce festival pour mettre en avant le [projet Rive de Gier](https://github.com/VCityTeam/UD-Demo-TIGA-Vallee-Du-Gier). L'intéret est d'ajouter une maquette Lego et d'améliorer leur dispositif de médiation numérique déjà mis en place avec un outil tangible pour aider à la compréhention de ce territoire. Mais aussi d'avoir un nouveau terrain d'expérimentation sur la représentation tangible d'un territoire et d'avoir un retour utilisateur sur cet outil. La maquette Lego sera composé d'une représentation d'une zone industrielle de Rive de Gier, de la table ainsi que son vidéo projecteur pour projeter de la donnée sur la maquette blanche. Le dispositif sera accompagné d'un support de questionnement sur cet outil pour apporter un retour utilisateur sur celui-ci.

## Install npm
For the npm installation refer [here](https://github.com/VCityTeam/UD-SV/blob/master/Tools/ToolNpm.md)

Required npm version: UD-Viz-Template has been reported to work with npm versions npm 6.X.

Reminder: `npm install -g npm@6.14.15` enables to [switch npm version](https://github.com/VCityTeam/UD-SV/blob/master/Tools/ToolNpm.md#task-switch-npm-version)

## Installing and running the demo

The template application can be locally (on your desktop) started in the following way
```
npm install
npm run debug      # integrates building
```
and then use your favorite (web) browser to open
`http://localhost:8000/`.

Note that technically the `npm run debug` command will use the [webpack-dev-server npm package](https://github.com/webpack/webpack-dev-server) that
 - runs node application that in turn launches a vanilla http sever in local (on your desktop) 
 - launches a watcher (surveying changes in sources) that
   - repacks and builds an updated bundle as soone as the sources are modified 
   - triggers a client reload (aka hot reload) 


