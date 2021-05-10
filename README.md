# manual-jira
JIRA를 활용한 이슈관리

## Posting
- `2021/4/20` [JIRA - SVN 커밋 시, 이슈번호 없을 경우 목록가져오기](https://blog.naver.com/jogilsang/222316201160)
- `2021/04/20` [JIRA - Issue의 첨부된 이미지 썸네일 최대크기 설정하기](https://blog.naver.com/jogilsang/222316187359)
- `2021/04/19` [JIRA - Word로 내보내기(export word) 이미지 오류 해결하는 법](https://blog.naver.com/jogilsang/222314888018)
- `2021/04/17` [JIRA - 댓글 Comment를 활용한 코드변경정보 관리, svnlook diff](https://blog.naver.com/jogilsang/222312827310)
- `2021/02/14` [JIRA - REST API를 활용한 이슈생성 및 이슈정보얻기](https://blog.naver.com/jogilsang/222243227224)

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
