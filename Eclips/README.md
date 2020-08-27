# Font 설정
    * Colors and fonts

# 웹 페이지 설정
    * Web Browser [external, Chrome]

# Encoding
    * Workspace Text encoding [UTF-8]

    * Web -> CSS, HTML, JSP

# Maven 로컬저장소 설정
        * Maven -> User Settings : [ C:\XX\apache\apache-maven-3.6.3\conf [sttings.xml] ]

# JSP Templates
    * HTML5
        <%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
        <%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c"%>
        <c:set var="rootPath" value='${pageContext.request.contextPath}' />

        <meta charset="UTF-8">
        <meta name='viewport' content='width=device-width, initial-scale=1'>
        <script src="https://code.jquery.com/jquery-latest.min.js"></script> // Jquery
        <script src="https://kit.fontawesome.com/c1d8b25418.js" crossorigin="anonymous"></script> // FontAwesome