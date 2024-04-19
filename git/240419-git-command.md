# Git 활용 방법 정리

## Git을 활용하는 이유

### Git은 로컬 디렉토리에서 일어난 작업을 Staging Area에 일시저장하게 한다.

#### 이후 Staging Area에 있는 코드와 작업 정보는 command를 기다리게 된다. command된 파일은 원격 저장소(github repository) 에 push되기를 기다리는 상태가 된다.

##### push가 이루어지게 되면 command 되어 있던 모든 파일이 github에 저장되게 된다.

# Git의 장점

## 1. 원래 상태로 되돌리기 가능
## 2. command history를 보며 수정 사항 확인 가능
## 3. 실험적인 코드가 실패했을 때 쉽게 폐기 가능.
## 4. 코드가 성공적일 경우 merge도 쉽게 가능.
## 5. 협업도 쉽게 가능.

# Clone방식을 활용한 Git 활용 순서

## 1. Github 홈페이지에서 repository를 생성한다.
## 2. repository의 url을 복사한다.(https로)
## 3. vim을 켠다.
## 4. clone을 위한 위치로 이동한다. (ex. Documents/dev/)
## 5. git clone url
## 6. 파일을 생성하거나 수정한다.
## 7. git status를 확인한다.
## 8. git add로 commit할 파일들을 추가한다.
## 9. git commit을 통해 push할 파일을 정리한다.
## 10. (중요) conventional commit을 통해 commit 문구를 잘 정리해서 업로드한다. 제목을 위에 쓰고, 두 칸 띄운 뒤 설명을 적어주면 되며 Conventional Commit의 규칙들이 있으니 잘 지켜야 한다.
## 11. git push origin main
## 12. 끝!
