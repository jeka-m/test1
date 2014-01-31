To use it with Maven. Add to pom.xml

Repository:
```xml
        <!-- Fugru repository, contains spring-social-vkontakte -->
        <repository>
            <id>snapshot</id>
            <name>Fugru Maven Snapshot Repository</name>
            <url>http://fugru.com/archiva/repository/snapshots</url>
            <releases><enabled>false</enabled></releases>
            <snapshots><enabled>true</enabled></snapshots>
        </repository>
	</repositories>
```
Dependency:
```xml
<dependencies>
        <dependency>
            <groupId>org.springframework.social</groupId>
            <artifactId>spring-social-vkontakte</artifactId>
            <version>${org.springframework.social.vkontakte-version}</version>
        </dependency>
```