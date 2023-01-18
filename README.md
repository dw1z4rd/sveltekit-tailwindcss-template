# Sveltekit App Template with TailwindCSS installed!

If you hate setting up tailwindcss each time you start writing a new sveltekit app, just clone this repo. It's already set up for you.
Just type:

```bash
# clone the repo into my-app directory
git clone git@github.com:dw1z4rd/sveltekit-tailwindcss-template.git my-app

# install deps
cd my-app && npm i

# build and run
npm run build && npm run preview
```

That's all there is to it. Now you can forget about writing a bunch of dumb css every time you want to design a component. If you're like me, you pretty
much have every tailwindcss class memorized and find it to be so much more convenient than having to manually write out a bunch of <style></style> tags and css for each .svelte file. Also, if you're like me, you *really* hate having to go through the installation of tailwindcss into your project each and every time.

I made this template to save me a bunch of work each time. You're welcome to do whatever you want with it. It's nothing fancy, just a blank sveltekit app with tailwindcss already installed and configured for you.

Also I've included dotenv as a dependency, so you can configure your app's environment without having to clutter your own. I haven't included the .env file here for obvious reasons, but you can totally write your own. The .gitignore file includes .env files so you don't have to worry about leaking
sensitive data in your repo.
