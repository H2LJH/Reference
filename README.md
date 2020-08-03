# Spring 3.9.13.RELEASE
    1. https://github.com/spring-projects/toolsuite-distribution/wiki/Spring-Tool-Suite-3 // Github
    2. https://download.springsource.com/release/STS/3.9.13.RELEASE/dist/e4.16/spring-tool-suite-3.9.13.RELEASE-e4.16.0-win32-x86_64.zip // Download
    
# Server
     * apache-tomcat-9.0.37

# Library
     * java-version 1.8
     * org.springframework-version 5.2.8 RELEASE
     * spring-jdbc ${org.springframework-version}
     * maven-compiler-plugin 3.8.1
     * maven-resources-plugin 3.1.0
     * commons-dbcp2 2.7.0
     * lombok 1.18.12
     * mysql-connector-java 8.0.21
     * mybatis-spring 2.0.5
     * mybatis 3.5.5
     * ojdbc6 11.2.0
     
# Manual Maven
    1. https://maven.apache.org/download.cgi
    
    2. apache-maven-3.6.3-bin.zip
    
    3. C:\XX\apache\apache-maven-3.6.3\conf [sttings.xml]
    
        <localRepository> 원하는 경로설정 </localRepository>
        </settings>
        
    4. C:\Users\H2LJH\.m2파일 삭제

# Eclipse Settings (로컬저장소 변경 Ojdbc 때문에)
    * Window -> Preferences : WorkSpace [UTF-8]
                              Web Browser [external, Chrome]
                              Web -> CSS [UTF-8], HTML [UTF-8], JSP [UTF-8]
                              Web -> HTML Files -> Editor -> Templates
    * Maven -> User Settings : [ C:\XX\apache\apache-maven-3.6.3\conf [sttings.xml] ]
