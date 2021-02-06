## HTML with Tailwindcss Practice Template

## Quick Guide

## Initialize project

### `yarn init`

This will take you through creating a package.json file, for our purposes I left all the values at their defaults. Once complete you should have a package.json file inside your project’s folder.

## yarn add tailwindcss autoprefixer

Now that Tailwind is installed, it’s time to start testing it out. To do this, we’ll create a basic website file structure.
Here’s how I set that up…
In the root of the project’s folder I made an index.html file and a styles folder. Inside of the styles folder, I created a styles.css file.

Once that was done, I added the following Tailwind directives into the styles.css

```js
@tailwind base;
@tailwind components;
@tailwind utilities;

```

In your command prompt window from before, select your styles folder that you made

```js
cd styles
```

With that selected, run the Tailwind CLI tool with the following command

```js
npx tailwind build styles.css -o output.css
```

If run successfully, you should now have an additional file in your styles folder named output.css which means you have successfully installed Tailwind CSS, all there is left to do is test to make sure.
