# publish-to-npm

publishing a package involves many steps. At the very least, you need to:

Run tests (if there are any)
Update version in package.json according to Semver
Create a git tag according to Semver
Push the package to Github
Push the package to npm
Create release notes for every update
It’s common to forget one of these things when we’re ready to push. Sometimes we npm publish and we enjoy a break. When we’re back, we screw ourselves for forgetting.


There’s an easier way. It’s with a tool called np.