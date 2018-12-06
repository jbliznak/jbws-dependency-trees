This repo contains output of dependency:tree goal executed in two usecases:

- For each module of the JBossWS project, ie. the goal is executed directly on the module pom.xml
- For each artifact of the JBossWS project, ie. the goal is executed on the pom.xml that has a dependency on the artifact

For the latter the content of the local repo is dumped too to see which artifacts were downloaded during resolution (eg. to see the overhead)

Whole set of dumps was executed on JDK8, JDK11 and IBM JDK8, results in respective branches.
