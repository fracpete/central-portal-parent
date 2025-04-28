# central-portal-parent
Parent POM for Maven Central Portal, mimicking [oss-parent POM](https://repo1.maven.org/maven2/org/sonatype/oss/oss-parent/).

## Usage

Use the following in your `pom.xml`:

```xml
  <parent>
    <groupId>com.github.fracpete</groupId>
    <artifactId>central-portal-parent</artifactId>
    <version>0.0.1</version>
  </parent>
```

## Documentation

* [difference between central and ossrh](https://central.sonatype.org/faq/what-is-different-between-central-portal-and-legacy-ossrh/)
* [self-service migration](https://central.sonatype.org/faq/what-is-different-between-central-portal-and-legacy-ossrh/#self-service-migration)
* [generate token](https://central.sonatype.com/account)
* [publish with maven plugin](https://central.sonatype.org/publish/publish-portal-maven/)
