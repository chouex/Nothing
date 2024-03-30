# An Lsposed api example

This module does nothing.

This is a template for new Lsposed module.

## How to Build io.github.libxposed:api:100

```
git clone --depth 1 https://github.com/libxposed/api.git libxposed/api
git clone --depth 1 https://github.com/libxposed/service.git libxposed/service

cd libxposed/api
./gradlew :api:publishApiPublicationToMavenLocal
cd ../service
./gradlew :interface:publishInterfacePublicationToMavenLocal
```