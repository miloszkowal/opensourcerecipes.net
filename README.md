# Open Source Recipes

Are you tired of bloat, trackers, and ads on recipe websites? Then Open Source Recipes is for you. This community-run site pools recipes from users like you who take the time to contribute them, and is dedicated to not have JS (the website should run fine without it at all), trackers, or ads of any kind - just the info you need to make food.

## Contributing

Interested in contributing a recipe? Follow these steps

1. Clone the repo
2. Add a new **folder** in the `recipes` folder (or if you have hugo installed, run `hugo new --kind recipe-bundle recipes/name-of-your-new-recipe-here` and replace `name-of-your-new-recipe-here` with your recipe name, and replace any spaces with dashes).
3. The folder should contain an `index.md` file with the recipe (see the code for examples) and a picture if you want (fewer pictures = less bloat)
4. If you take a recipe from elsewhere on the internet, _please_ link back in the `index.md` file. You can do so with the `authorName`, `authorURL`, `sourceName` and `sourceURL` attributes.

If you're interested in making the website better, you can also contribute PRs to improve the site itself.
