Here we have created a simple NPM package. Anyone can install it and use it.

Once you have published the package, you can refactor the code or add functionality. If you do this, change the version number in the package.json before publishing.

It is also suggested that you add a README.MD, a markdown file, that gives a description and some examples of how to use your package.

### Publish

- **Export**

Use `module.exports` to export functions that are to be used from the package

```
module.exports = removeArrayDuplicates
```

- **Configure package.json**

Name must be unique in NPM registry.

Change any other information that is necessary.

- **Login to NPM registry**

```
npm login
```

- **Publish package***

```
npm publish
```

### Making Changes
If you need to make changes,

- Make the changes.
- Open the package.json and change the version number.
- Login to the NPM registry and run npm publish again.

## Standard build process for updates and contributing to open source projects
 Follow this [link](https://cloudfour.com/thinks/how-to-publish-an-updated-version-of-an-npm-package/).
 
# References
1. [How to Publish an Updated Version of an npm Package](https://cloudfour.com/thinks/how-to-publish-an-updated-version-of-an-npm-package/).
2. [Publish React components as an npm package](https://levelup.gitconnected.com/publish-react-components-as-an-npm-package-7a671a2fb7f).
3. [Use Github branch as dependency in package.json](https://medium.com/@jonchurch/use-github-branch-as-dependency-in-package-json-5eb609c81f1a).
