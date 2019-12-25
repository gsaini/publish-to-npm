# publish-to-npm

publishing a package involves many steps. At the very least, you need to:

1. Run tests (if there are any)
2. Update version in package.json according to Semver
3. Create a git tag according to Semver
4. Push the package to Github
5. Push the package to npm
6. Create release notes for every update

It’s common to forget one of these things when we’re ready to push. Sometimes we npm publish and we enjoy a break. When we’re back, we screw ourselves for forgetting.


There’s an easier way. It’s with a tool called np.
