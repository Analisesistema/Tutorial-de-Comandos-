# Tutorial-de-Comandos-

------------------------------------------------------------------------------------------------
comandos para formatar na tela, a data é LocalDate
<dependency>
    <groupId>org.thymeleaf.extras</groupId>
    <artifactId>thymeleaf-extras-java8time</artifactId>
    <version>3.0.4.RELEASE</version>
</dependency>
th:text="${#temporals.format(ordemservico.dataAbertura,'dd-MM-yyyy')}"
------------------------------------------------------------------------------------------------
