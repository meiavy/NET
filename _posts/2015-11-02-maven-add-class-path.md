---
date: 2015-11-02 11:03:30+00:00
layout: post
title: Maven项目中增加classpath
thread: 164
categories: 教程
tags: maven classpath
---

# Maven项目中可以按如下方法增加classpath

<plugin>
	<groupId>org.apache.maven.plugins</groupId>
	<artifactId>maven-jar-plugin</artifactId>
	<version>2.4</version>
	<configuration>
		<archive>
			<index>false</index>
			<manifest>
				<classpathPrefix>lib/</classpathPrefix>
				<addClasspath>true</addClasspath>
				<mainClass>longtv.App</mainClass>
			</manifest>

##			<manifestEntries>
##				<Built-By>Me</Built-By>
##				<Class-Path>.</Class-Path>
##			</manifestEntries>

		</archive>
	</configuration>
</plugin>



