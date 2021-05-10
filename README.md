# manual-jira
JIRA는 아틀라시안이 개발한 사유 이슈 추적 제품이다. 버그 추적, 이슈 추적, 프로젝트 관리 기능을 제공하는 소프트웨어이다

## Posting
- `2021/4/20` [JIRA - SVN 커밋 시, 이슈번호 없을 경우 목록가져오기](https://blog.naver.com/jogilsang/222316201160)
  ![image](https://user-images.githubusercontent.com/20831981/117681199-cfb3d700-b1ec-11eb-91e1-712b1a3815c2.png)
- `2021/04/20` [JIRA - Issue의 첨부된 이미지 썸네일 최대크기 설정하기](https://blog.naver.com/jogilsang/222316187359)
  ![image](https://user-images.githubusercontent.com/20831981/117681319-f4a84a00-b1ec-11eb-88be-f654e07966bc.png)
- `2021/04/19` [JIRA - Word로 내보내기(export word) 이미지 오류 해결하는 법](https://blog.naver.com/jogilsang/222314888018)
- `2021/04/17` [JIRA - 댓글 Comment를 활용한 코드변경정보 관리, svnlook diff](https://blog.naver.com/jogilsang/222312827310)
  ![image](https://user-images.githubusercontent.com/20831981/117681535-27524280-b1ed-11eb-8348-4e8e4a6d11cd.png)
- `2021/02/14` [JIRA - REST API를 활용한 이슈생성 및 이슈정보얻기](https://blog.naver.com/jogilsang/222243227224)
  ![image](https://user-images.githubusercontent.com/20831981/117681454-16a1cc80-b1ed-11eb-936c-59be94eab214.png)


---

## Reference
- [jira-rest-api-examples](https://developer.atlassian.com/server/jira/platform/jira-rest-api-examples/)   
- [jira-rest-v2-doc](https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-workflow-schemes/)  
- [BP-jira-jenkins](https://issues.jenkins.io/projects/JENKINS/issues/JENKINS-37984?filter=allopenissues)
- [BP-jira-atlassian](https://jira.atlassian.com/browse/JRACLOUD-10156)

---

## Macro
### panel
https://confluence.atlassian.com/doc/panel-macro-51872380.html   
```
{panel:title=My title|borderStyle=dashed|borderColor=blue|titleBGColor=#e7f4fa|titleColor=white|bgColor=#E7F4FA}
A formatted panel
{panel}

{panel:title=My title|titleBGColor=#3C78B5|titleColor=white|bgColor=#E7F4FA}
A formatted panel
{panel}

{panel:title=My title|titleBGColor=#F0F0F0|titleColor=white|bgColor=#E7F4FA}
A formatted panel
{panel}

div class="panel" style="background-color: #e7f4fa
panelContent" style="background-color: #E7F4FA
```
