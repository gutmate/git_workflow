## git 협업 과정

1. Fork
2. clone, remote설정
3. branch 생성
4. 수정 작업 후 add, commit, push
5. Pull Request 생성(GitHub 기능)
6. 코드리뷰, Merge Pull Reqest
7. Merge 이후 branch 삭제 및 동기화

### Q)

1. 로컬 브랜치에서 작업 중인 경우, 원본 프로젝트의 sync는 언제? 어떻게? <br>
» 협업의 경우, PR이 머지되면 각자 자신의 로컬 master에 해당 내용을 자주 반영하는게 좋음<br>
» 내가 작업중인 브랜치는 git rebase master를 통해서 그래프 최상단으로 올리는 것이 히스토리 관리가 깔끔해짐

## git 명령어

- 최근 커밋 취소
```bash
git reset HEAD^
```

- 최근 수정 사항 삭제
```bash
git checkout <file name>
```

- branch 병합하기
```bash
git checkout <병합 베이스 branch>
git merge <병합하고 싶은 내용이 있는 branch>
```

<병합하고 싶은 내용이 있는 branch> 소스를 <병합 베이스 branch> 에 추가 한다.

- Pull Request 보내기
커맨드라인으로는 안되는 듯? - Git 의 기능이 아닌 GitHub의 기능으로 보임


## 이슈사항

ISSUE
