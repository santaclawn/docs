Expand **Gradle Scripts**, open **build.gradle (Module: app)**. You will already have configured Amplify by following the steps in the [Project Setup walkthrough](~/lib/project-setup/create-application.md).

Add Predictions by adding these libraries into the `dependencies` block:

```groovy
dependencies {
    // Add these lines in `dependencies`
    implementation 'com.amplifyframework:aws-predictions:1.17.8'
    implementation 'com.amplifyframework:aws-auth-cognito:1.17.8'
}
```

`aws-auth-cognito` provides authentication for the backend services used by `aws-predictions`.

Click **Sync Now**.
