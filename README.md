# Create react packages from old versions

Unfortunately, there isn't really an easy way to install a particular old
version of ReactJS.

Here are a set of compatible configurations of ReactJS created using `npx create-react-app`.

## Use
```
git clone git@github.com:davidnewcomb/npx-create-react-app-pacakges.git
cd packages_json/16/16.13.1
npm install
# or
yarn install
```

## Why
I wanted to have a quick play with [react-html-parser](https://www.npmjs.com/package/react-html-parser)
but the current `npx create-react-app` installs ReactJS 18 and [react-html-parser](https://www.npmjs.com/package/react-html-parser) requires version 16.
So I hop over to the various project pages and react-html-parser has been in compatible since react 16.
Ok, so how can we install react 16? Accrording to [StackOverflow](https://stackoverflow.com/a/67390700/52070) you can't.
I started hunting around for another solution but I could feel my life ebbing away.

I had a look amongst my old projects and found a few that were created with version 16.
Hurray! Copied the package.json into position and voila! Loads less hassle!

So I'm sharing these in case they are useful to others.

## Help
If you know a nice easy way to create a react project with a particular version
then please create an issue and let me know. With one thing and aother it seems to
change from time to time, so maybe can can capture that here too.
