# Estudos Java

### Este repositório é dedicado ao meus estudos da linguagem de programação Java. Aqui você encontrará recursos úteis para começar a aprender Java, bem como configurar seu ambiente de desenvolvimento.

## Configurando o Ambiente
- Para começar a programar em Java, você precisará configurar seu ambiente de desenvolvimento. Aqui estão os passos básicos para configurar seu ambiente:

### 1. Instalar o JDK (Java Development Kit)
- O JDK é necessário para compilar e executar programas Java. Você pode baixar e instalar o JDK mais recente do site oficial da Oracle:

>[Download JDK](https://www.oracle.com/br/java/technologies/downloads/)
>Versão usada JDK-21

### 2. Configurar Variáveis de Ambiente
- Depois de instalar o JDK, você precisará configurar as variáveis de ambiente JAVA_HOME e PATH:

>Em variaveis de sistema crie a variavel JAVA_HOME, essa deve estar toda maiuscula e separado por underscore.
>Com a variavel de sistema JAVA_HOME aponte para o diretório de instalação do JDK (C:\Program Files\Java\jdk-21).

>Em variaveis de sistema edite a variavel Path.
>Adicione o diretório "bin" do JDK a sua variavel de sistema Path (%JAVA_HOME%\bin) e depois o diretório de instalação do JDK (C:\Program Files\Java\jdk-21), não exclua nada no diretorio, apenas adcione.

### 3. Instalar um Editor de Código ou IDE
- Você pode optar por usar um editor de código simples, como Visual Studio Code, ou uma IDE mais completa, como IntelliJ IDEA ou Eclipse.
NO caso estou usando o Eclipse IDE for Java EE Developers 

>[Download Eclipse](https://www.eclipse.org/downloads/packages/release/kepler/sr2/eclipse-ide-java-ee-developers)

### 4. Apache Tomcat
- Para desenvolver aplicativos web Java EE, precisará de um servidor web. O Apache Tomcat é uma opção popular e leve.
>- Baixe o arquivo e descompacte no disco local
>- Apos isso abra a pasta do Apache Tomcat descompatada, abra a pasta "bin" e procure e execute o arquivo "starup.bat"
>- Para fazer a configuração do servidor Apache Tomcat, veja qual a versão mais atualizada que sua IDE aceita, no caso a versão mais atual que minha IDE aceita é a apache-tomcat-10.1.19

>[Download Apache Tomcat](https://tomcat.apache.org/download-10.cgi)
>Versão usada Apache Tomcat 10.1.19

### 5. PostgreSQL
- Para desenvolver sera necesario um banco de dados, sera utilizado o banco de dados relacional PostgreSQL. Você pode escolher entre diferentes versões do PostgreSQL, dependendo das suas necessidades específicas.

>PostgreSQL 9.5: Uma versão mais antiga, estável e amplamente utilizada.
>
>[Download PostgreSQL 9.5](https://sbp.enterprisedb.com/getfile.jsp?fileid=1257550)

>PostgreSQL 16.2: A versão mais recente, com novos recursos e aprimoramentos.
>
>[Download PostgreSQL 16.2](https://sbp.enterprisedb.com/getfile.jsp?fileid=1258893)

### 6. Configurar o Projeto
- Depois de instalar o ambiente, crie um novo projeto Java em seu editor de código ou IDE preferido. Configure o Tomcat como seu servidor de aplicativos web e o PostgreSQL como seu banco de dados, conforme necessário.

### Aqui estão alguns recursos úteis para aprender Java:

- [Java Documentation](https://docs.oracle.com/en/java/): A documentação oficial da Oracle para a plataforma Java.
- [Java Tutorials](https://docs.oracle.com/javase/tutorial/): Tutoriais abrangentes para aprender Java, fornecidos pela Oracle.

### Contribuição
- Se você encontrar recursos adicionais úteis ou tiver sugestões de aprimoramento, sinta-se à vontade para contribuir para este repositório através de pull requests.

### ERROR

- Erro na inicialização do Tomcat

>Several ports (8005, 8080) required by Tomcat v10.1 Server at localhost are already in use. The server may already be running in another process, or a system process may be using the port. To start this server you will need to stop the other process or change the port number(s).


[Resolução](https://cursos.alura.com.br/forum/topico-problema-rodar-tomcat-no-eclipse-17281)


### Licença
- Este repositório é distribuído sob a licença MIT. Sinta-se à vontade para usá-lo conforme necessário.
