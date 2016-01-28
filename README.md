# My Gulp Webapp Starter

About
---
Moves and compiles src files to target/ folder, and runs a Browser Sync server on **localhost:6112**

Instructions
---

1. git clone https://github.com/robinsonbd2/myGulp MyFirstGulpWebapp

2. npm install gulp

3. npm install gulp-util gulp-sass gulp-autoprefixer gulp-cssnano gulp-jshint gulp-concat gulp-uglify gulp-imagemin gulp-notify gulp-rename gulp-cache gulp-jshint browser-sync del --save-dev

To run:
> gulp

TODO
---
1. Add sourcemaps/img maps
2. Add Gulp project variants as github branches.
3. Modify Gulpfile for Hippo Community Edition (+base directory will move to frontend folder)



*Last Updated: January 27, 2016*



Other Versions (Found in branches or not yet released)
===

Hippo Community Edition Instructions
---
1. [Create the project](http://www.onehippo.org/trails/getting-started/creating-a-project.html).
> mvn archetype:generate \
> -DarchetypeGroupId=org.onehippo.cms7 \
> -DarchetypeArtifactId=hippo-project-archetype \
> -DarchetypeVersion=3.1.1 \
> -DarchetypeRepository=http://maven.onehippo.com/maven2

2. [Build the project](http://www.onehippo.org/trails/getting-started/building-a-project.html).
> cd myhippoproject
> mvn clean verify

3. [Run the project](mvn -Pcargo.run -Drepo.path=storage).
> mvn -Pcargo.run
> http://localhost:8080/cms/?0
> **Usernames**
> admin / admin
> editor / editor
> author / author
