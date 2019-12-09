# repository
发布
```
打包发布到仓库
mvn clean deploy -DaltDeploymentRepository=TridentHuang-repository::default::file:/soft/maven/github/repository
```
使用
```
1，在pom中添加仓库地址
	<repositories>
		<repository>
			<id>repository</id>
			<url>https://raw.github.com/TridentHuang/repository/master</url>
		</repository>
	</repositories>
2，添加依赖包
<dependency>
			<groupId>cn.fanyu</groupId>
			<artifactId>common</artifactId>
			<version>1.2</version>
		</dependency>
```
