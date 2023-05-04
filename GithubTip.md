해당 디렉터리를 push하고 싶다면  
cd 명령어를 통해서 해당 디렉터리로 이동 후  
git init을 하라.

git checkout -b branchname 은 새로운 브랜치 생성  
git checkout branchname 은 해당 브랜치로 이동  

git remote -v 는 레포지토리주소에 연결된 원격저장소 이름 정보    

git push -u 원격저장소이름 브랜치이름 에서 굳이 -u를 붙이는 이유는  
처음에는 두 가지 인자를 전달하더라도 그 다음부터는 두 가지 인자에 대한 정보를 생략해도  
해당 원격저장소 브랜치로 push할 수 있다.  

visual code로 파일 생성 및 수정 후 save해주지 않으면  
add 되지 않으므로 주의하라.