1. Create package json file

npm init --yes

2. Install sass

npm i node-sass

3. Compile scss to css. Whenever you make modifications to the scss file, run the command below.

node-sass -o css scss/main.scss

4. Or if you add -w to the end of the above cmd, you can run it only once, as seen below.

node-sass -o css scss/main.scss -w

5. Alternatively, include the above command in the package.json and run the command below. Whenever starting the project, you must run the cmd.

npm run watch