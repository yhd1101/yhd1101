## Hi there 👋

 **마찰력 없는 인앱경험**을 발견하면 정말 좋아합니다.
 그런 제품을 만들기 위해, 일을 할 때 **본인만의 해석과 철학**을 팀원과 먼저 **공유**합니다.
 초기 제안 보다 **더 나은 해결 방법을 제안**합니다.
 제안이 실행 단계로 전환됐을 때 **지치지 않고 완수**하는 사람입니다.
 문제를 해결해나가는 **집요함**이 있습니다.
 


<a href="https://velog.io/@yhd1101/posts">
    <img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=FFFFFF"/>
</a>
 
### **About me:)**

``` java
package introduction.domain;

@Builder
class Member {
    String name;
    String job;
    String[] developmentFields;
    String[] languages;
    String[] backendSkills;
    String[] devOpsSkills;
    String[] collaborationTools;
    String[] interests;
}

public class Main() {
    public static void main(String[] args) {
    
        Member minsuk = Member.builder()
                .name("양한동")
                .job("Software engineer🧑🏽‍💻")
                .developmentFields(new String[]{"Back-end🔭"})
                .languages(new String[]{"Java☕", "TypeScript"})
                .backendSkills(new String[]{"Spring🌱", "Dropwizard", "NestJS🔥", "JPA🔧", "MyBatis🦤", "Junit5️⃣", "Mockito🍸", "Gradle🐘", "OpenSearch🔹"})
                .devOpsSkills(new String[]{"Ubuntu🐺", "Github Actions♾️", "MariaDB🦭", "Docker🐋", "AWS EC2☁️", "S3", "CodeDeploy, PostgreSQL🐘"})
                .collaborationTools(new String[]{"Slack📑", "Notion","Git", "Intellij"})
                .interests(new String[]{"정리", "실험", "습관", "마찰력"})
                .build();

        introduce(minsuk);
    }
}

```

-->
