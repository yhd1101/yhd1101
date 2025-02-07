## Hi there 👋

🚀 "깊이 파고들고, 함께 성장하는 개발자" <br/>
궁금한 게 생기면 끝까지 파고드는 사람입니다.
"왜?"라는 질문을 멈추지 않으며, 단순한 해결책이 아닌 더 나은 방향을 찾는 과정을 즐깁니다.

기술은 혼자서만 잘한다고 완성되지 않는다고 생각합니다.
좋은 제품을 만들기 위해서는 팀원들과의 소통이 필수적이며,
서로의 아이디어를 공유하고 조율하는 과정을 통해 최선의 해결책을 찾아가는 것을 중요하게 생각합니다.
 


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
    
        Member handong = Member.builder()
                .name("양한동")
                .job("Software engineer🧑🏽‍💻")
                .developmentFields(new String[]{"Back-end🔭"})
                .languages(new String[]{"Java☕", "TypeScript"})
                .backendSkills(new String[]{"Spring🌱","NestJS🔥", "JPA🔧", "TypeOrm🔍","MyBatis🦤", "Junit5️⃣","Gradle🐘"})
                .devOpsSkills(new String[]{"Ubuntu🐺", "Github Actions♾️", "MariaDB🦭", "Docker🐋", "AWS EC2☁️", "S3", "CodeDeploy, PostgreSQL🐘"})
                .collaborationTools(new String[]{"Slack📑", "Notion","Git", "Intellij"})
                .interests(new String[]{"문제 해결","대용량 데이터", "클린 코드", "백엔드 아키텍처", "성장", "기술 공유"})

                .build();

        introduce(handong);
    }
}

```


