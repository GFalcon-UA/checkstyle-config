# checkstyle-config
Configurations for CheckStyle plugin

## Usage

```xml
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-checkstyle-plugin</artifactId>
    <dependencies>
        <dependency>
            <groupId>com.puppycrawl.tools</groupId>
            <artifactId>checkstyle</artifactId>
            <version>${checkstyle.version}</version>
        </dependency>
        <dependency>
            <groupId>ua.com.gfalcon</groupId>
            <artifactId>checkstyle-config</artifactId>
            <version>${checkstyle-config.version}</version>
        </dependency>
    </dependencies>
    <configuration>
        <configLocation>checkstyle.xml</configLocation>
    </configuration>
</plugin>
```
