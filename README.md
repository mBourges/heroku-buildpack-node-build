# heroku-buildpack-node-build
Buildpack for Heroku to execute `npm run build` 

## Usage

1. Add this buildpack to your heroku application:
   ```bash
   $ heroku buildpacks:add https://github.com/mBourges/heroku-buildpack-npm-build
   ```
2. Add a `build` script into your `package.json` file
3. Deploy to Heroku.