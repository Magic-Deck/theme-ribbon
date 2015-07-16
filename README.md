# Ribbon theme

Ribbon theme for the Ponyshow presentation engine.

[![Get it on npm](https://nodei.co/npm/ponyshow-theme-ribbon.png)](https://nodei.co/npm/ponyshow-theme-ribbon/)

## Run

To see this theme in action:

- Run a presentation using the Ponyshow CLI or Ponyshow App
- Set the theme property for a slide ```theme:ribbon``` or use the CLI to set the property ```pony config set theme=ribbon```
- Run the Ponyshow markdown file (```deck.md```)
- Click any slide to enter presentation mode
- Use arrow keys or presenter remote to navigate
- Press `Esc` to exit presentation mode

## Build

The source of this theme lives under ```src``` folder.  Compress to ```dist/css/screen.css``` using ```gulp```.

To start, you should run ```npm install .``` to install dependencies.  Then simply run..

```
$ gulp
```

## License

Copyright © 2015 Semantic Press, Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.