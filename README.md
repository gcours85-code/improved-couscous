# improved-couscous
registries:   maven-artifactory:     type: maven-repository     url: https://acme.jfrog.io/artifactory/my-maven-registry     username: octocat     password: ${{secrets.MY_ARTIFACTORY_PASSWORD}}     replaces-base: true
