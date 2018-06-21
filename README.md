# repository
My Maven Repository,Please Add flowing content in your parent pom.xml

```
<repository>
	<id>tomaer-repository-releases</id>
        <name>mvn-repository</name>
        <url>https://raw.githubusercontent.com/tomaer/repository/release</url>
        <releases><enabled>true</enabled></releases>
        <snapshots><enabled>false</enabled></snapshots>
</repository>
<repository>
	<id>tomaer-repository-snapshots</id>
        <name>mvn-repository</name>
        <url>https://raw.githubusercontent.com/tomaer/repository/snapshot</url>
        <releases><enabled>false</enabled></releases>
        <snapshots>
		<enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
        </snapshots>
</repository>
```
