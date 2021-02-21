# NodeZero

NodeZero is a PrimeFace Spring Boot application written to Facilitates tracking the Factory Inventory and employees' daily works.

## Installation

In Github Master branch has been defaulted.

(01) Clone the repository using the below command,

```bash
git clone https://github.com/gilimalagep/NodeZero.git
```
(02) if you are using java 10 or above below changes need to done in POM.xml
```xml

       <dependency>
		    <groupId>org.projectlombok</groupId>
		    <artifactId>lombok</artifactId>
		    <version>1.18.18</version>
		</dependency>

		<plugin>
			<groupId>org.apache.maven.plugins</groupId>
			<artifactId>maven-compiler-plugin</artifactId>
				<version>3.5.1</version>
						<configuration>
							<source>11</source>
							<target>11</target>
						</configuration>
		 </plugin>
		
```



(03) Change the folder, and execute the command 
```bash 
cd serenity/
```
Make the project IDE specific using mvn command , 
for the IDEA case it is 
```bash
mvn idea:idea
```  
For the eclipse it is 
```bash
mvn eclipse:eclipse
```  

(03) Import the project to IDE and  Build the project using below mvn command
```bash
mvn clean install
``` 
(04) Run the project using


```bash
mvn spring-boot:run

```
