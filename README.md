# Tutorial-de-Comandos-

------------------------------------------------------------------------------------------------
comandos para formatar na tela, a data é LocalDate
<dependency>
    <groupId>org.thymeleaf.extras</groupId>
    <artifactId>thymeleaf-extras-java8time</artifactId>
    <version>3.0.4.RELEASE</version>
</dependency>
th:text="${#temporals.format(data,'dd-MM-yyyy')}"
------------------------------------------------------------------------------------------------

 git push origin master
To https://github.com/Analisesistema/app.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/Analisesistema/app.git'

solução: git add .
         git commit -m "lista de alteração"
         git push origin master
