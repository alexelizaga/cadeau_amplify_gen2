# cadeau_amplify_gen2

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Amplify Sandbox
```
npx amplify sandbox --config-format=dart --config-out-dir=lib
```

To generate the model classes out of GraphQL schema, you can run the following command:
```
npx amplify generate graphql-client-code --format=modelgen --model-target=dart --out=lib/models
``