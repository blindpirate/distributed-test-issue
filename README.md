### Readme

This is a reproducer for https://github.com/gradle/dotcom/issues/5958

Step to reproduce:

1. Configure GE crendentials to run distributed test.
2. `./gradlew test`

You'll get:

```
* What went wrong:
Execution failed for task ':test'.
> No tests found for given includes: 
```
