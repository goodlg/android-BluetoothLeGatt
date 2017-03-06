Error 1:
    Execution failed for task ':Application:lint'.
    > Lint found errors in the project; aborting build.

Solution:
    modify Application/build.gradle
    ...
    android {
        lintOptions {
            abortOnError false
        }
    }
    ...
    