# Forked from https://github.com/Roslovets-Inc/strapi-plugin-ckeditor5

Differences in this fork include:

- Updated CKEditor to v29 from v27
- The above update gives us access to the source editing plugin which is installed
- Added a couple of other plugins like the highlight and find and replace
- Changed the default toolbar a bit. Other changes can be seen in the commit history

## Installing

1. Add to **package.json**. The second install creates another module from the first to work with Strapi's autoloading of the plugins by name:
   `"@tablufc88/strapi-plugin-ckeditor5": "^1.11.1", "strapi-plugin-ckeditor5": "npm:@tablufc88/strapi-plugin-ckeditor5",`

2. Add to **.npmrc** in project folder to use the Github registry:
   `@tablufc88:registry=https://npm.pkg.github.com/`

3. Run `yarn` or `npm i`
