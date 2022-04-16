# WorkAdventure Map for DEVConnect

![image](https://user-images.githubusercontent.com/111600/163675019-9b2c1086-51b4-4cf5-a24c-97a054265d42.png)

This is a [WorkAdventure](https://workadventu.re) map for [DEVConnect](https://devconnect.org/)

To understand how contribute, follow the tutorial at [https://workadventu.re/map-building](https://workadventu.re/map-building).

## Local Installation for testing

With npm installed (comes with [node](https://nodejs.org/en/)), run the following commands into a terminal in the root directory of this project:

```shell
npm install
npm run start
```

The project will run at http://localhost:8080/

## Licenses

This project contains multiple licenses as follows:

* [Code license](./LICENSE.code) *(all files except those for other licenses)*
* [Map license](./LICENSE.map) *(`map.json` and the map visual as well)*
* [Assets license](./LICENSE.assets) *(the files inside the `src/assets/` folder)*

### About third party assets

If you add third party assets in your map, do not forget to:
1. Credit the author and license with the "tilesetCopyright" property present in the properties of each tilesets in the `map.json` file
2. Add the license text in LICENSE.assets
