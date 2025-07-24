# mvn-repo
Personal Maven repository for artifacts that are not on Maven Central

To use this repo add the following to pom.xml:
```
<repositories>
    <repository>
        <id>pvf2005-mvn-repo</id>
        <url>https://raw.githubusercontent.com/pvf2005/mvn-repo/main/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>

```
Afterwards dependencies can be added as usually. For example:
```
    <dependency>
      <groupId>com.github.pvf2005</groupId>
      <artifactId>genericaimodelclient</artifactId>
      <version>0.0.1</version>
    </dependency>
```
