Dependency list that's going to be imported into whatever project is being used.

To use:
In the `buildscript` block at your project level build.gradle, add:
`apply from: 'gradleScripts/dependencies.gradle'`

such as:
`
buildscript {
    apply from: 'gradleScripts/dependencies.gradle'
    .
    .
    .
`

Then add them in your app level gradle file with:
`    api constraintlayout.lib
`
