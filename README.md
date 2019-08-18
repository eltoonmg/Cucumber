1 - Baixar JDK

2 - Baixar o eclipse

3 - Criar projeto maven no eclipse
  File -> new -> Other -> Maven Project

4 - Selecionar as opções 
  - Create a simple project(Skip archetype selection)
  - Use Default Workspace location
  - Group Id: br.com.tester.kpages
  - Artifact Id: TesteListaProdutos

5 - Inserir no POM.xml
  <project xmlns="http://maven.apache.org/POM/4.0.0"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>br.com.kpages.tester</groupId>
	<artifactId>TesteIgnicaoDigital</artifactId>
	<version>0.0.1-SNAPSHOT</version>

		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-java</artifactId>
			<version>1.2.5</version>
		</dependency>

		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-junit</artifactId>
			<version>1.2.5</version>
			<scope>test</scope>
		</dependency>

		<dependency>
			<groupId>org.seleniumhq.selenium</groupId>
			<artifactId>selenium-java</artifactId>
			<version>3.141.59</version>
		</dependency>

		<dependency>
			<groupId>commons-io</groupId>
			<artifactId>commons-io</artifactId>
			<version>2.6</version>
		</dependency>
	</dependencies>
</project>

6 - Vá em Help, Eclipse Marketplace, procure por cucumber e instale o plugin "Cucumber Eclipse Plugin 0.0.23..."

7 - Clique com o botão direito do mouse no projeto, clicar na opção Properties, Resources, na grid Text file encoding, selecione a opção Other e mude para UTF-8

8 - 
