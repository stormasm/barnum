

#### To make changes to the barnum website

Simply make changes in the src directory.   
And then run this command:   

```
mdbook build -d ./docs
```

This command will blow away
```
docs/CNAME
```

And then simply restore it by running the command:

```
gco docs/CNAME
```

Commit all changed files and your new website will be
up and running shortly !

In the theme directory the following changes have been made...

Which enables these trivial features changes...

 * The sidebar is now always open by default.
 * The default size of the sidebar is changed from 300px to 200px

I noticed that when you actually toggle the sidebar to closed
and shutdown your browser and bring it back up that it is still
closed so that is kind of cool.

### References

[sidebar open by default](https://github.com/stormasm/mdBook/commit/53abee11b2f70c435c99ebe151cb75f77e191f98)

```
mdbook build -d ./docs
```

[github pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain)

[how to setup google domain for github pages](https://dev.to/trentyang/how-to-setup-google-domain-for-github-pages-1p58)
