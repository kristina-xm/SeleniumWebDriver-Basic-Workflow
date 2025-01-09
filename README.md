The repository contains three separate projects, each with its own test suite. The pipelines are designed to automate the build and test process.

### GitHub Actions pipeline
It has 2 jobs: **Build** and **Test**. 
**Test** executes after a successful build.

### Jenkins pipeline
Runs the test suites for all three projects in parallel.
