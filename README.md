# Spring Cloud 2023.0.x and Frontend(react.js | vue.js | angular)

This is a work in progress.

I will create `spring-cloud2025-estore` next year, hence use `cloud2024` in the name.

1. Spring Cloud 2023.0.0
2. Spring Authorization Server 1.2.3
3. Frontend: React.js 18 + Vue.js 3 + Angular 17
4. OpenID Connect with PKCE

## Up and running

This multi-module project is created by my plugin [billcat-maven-archetypes](https://github.com/billcat-projects/billcat-maven-archetypes), you can install it and use locally. It's very simple to use.

```shell
# Option 1: Install the above archetype plugin and create your estore project from scratch 
mvn archetype:generate \
-DarchetypeGroupId=net.billcat.archetypes \
-DarchetypeArtifactId=multi-module-cloud-jpa \
-DarchetypeVersion=1.0.0 \
-DgroupId=com.yourcompany.demo \
-DartifactId=your-project-name \
-Dversion=1.0.0-SNAPSHOT

# Remove extra parent tag (see Known issues in my archetype plugin project)
open `your-project-name-dependencies/pom.xml` and remove `<parent>` tag

# Option 2: Clone this project directly
git clone https://github.com/billcat-projects/spring-cloud2024-estore.git

# Finally: Now everything is the same
cd spring-cloud2024-estore
mvn clean install
```

## Issues and comments

Leave your comments and suggestions in the issues area. For example, if you want a slightly different tech stack.

Also, if you like my demo, ~~please consider buying me a coffee~~. Please follow and star :).

## License

[MIT](./LICENSE)
