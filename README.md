# Vector Tile PBF viewer

The tool helps you plot one pbf file containing data encoded with [Mapbox Vector Tile specification](https://github.com/mapbox/vector-tile-spec)

Data from PBF is plotted on a canvas.

## Demo
Check the live working demo https://mapcherry.github.io/vt-pbf-viewer/


![Canvas representation of pbf](./src/assets/pbfplotted.png)


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```
### node 18 + instructions
after running npm install and npm run serve , i got ssl error message (bug fixed node 17+)
to get the code to run I ran
```
npm audit fix --force
```

and changed the eslint version to 7.5.0 as in this fork
