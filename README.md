# Maven versions

```bash
./mvnw build-helper:parse-version versions:set -DnewVersion='${parsedVersion.majorVersion}.${parsedVersion.minorVersion}.${parsedVersion.incrementalVersion}'-xyz
./mvnw clean package
./mvnw versions:revert
```