* git

working directory (working tree)  "red"   |

↓$ git add                                                      | (git status로 변경사항 조회=로그 확인)

staging area(index)   "green"                     |

↓$ git commit

repository ( git log로 변경사항 조회=버전 확인)

git status

커밋 X  ##untracked files##

커밋 0, 스테이징 에리어X  ##changes not staged for commit##

스테이징 에리어에 있음 ##changes to be committed## 



* 원격 저장소 (git remote add origin https~)

got hub, git lab, bitbucket

$ git clone :원격 저장소 복제하여 사용

$ push/ pull :원격과 로컬 저장소 둘 다 있을 경우

로컬과 원격 연결 : 가장 먼저 git status - git add - git status -  git commit

원격 저장소에서 직접 수정 X

모든 파일 변경/수정/삭제/생성 -> 로컬에서 & 커밋 열심히!!



git torvalds google -tech talk