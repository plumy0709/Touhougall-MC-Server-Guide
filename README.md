# 모드 팩 설치 하는 법
모드팩은 버전 1.18.1 기준
두 가지 방법이 있음.

# 짚고 넘어가야 할 사실: 당연하게도 구버전 모드가 마인크래프트 파일에 깔려있으면 당연히 버전충돌로 실행이 안된다. 전부 다 따라해보고 중간에 막혀서 안되면 이걸 확인하고 이미 깔려있던 모드를 삭제하고 신버전 모드를 실행하길 바람.  


# 1: MultiMC로 모드 파일 실행
먼저 아래에 주어진 url 중 자신의 OS에 맞는 url을 클릭한다.  
Windows: https://files.multimc.org/downloads/mmc-stable-win32.zip  
Mac OS X: https://files.multimc.org/downloads/mmc-stable-osx64.tar.gz  
Linux(Debian/Ubuntu): https://files.multimc.org/downloads/multimc_1.6-1.deb  
Arch Linux: https://github.com/MultiMC/multimc-pkgbuild  
Linux Binary Tarball (32-bit): https://files.multimc.org/downloads/mmc-stable-lin32.tar.gz  
Linux Binary Tarball (64-bit): https://files.multimc.org/downloads/mmc-stable-lin64.tar.gz  
  
그리고 아래에 주어진 url을 클릭하여 모드팩을 다운로드 한다.  
https://www.curseforge.com/minecraft/modpacks/better-minecraft-fabric/download/3622846  
  
아래에 주어진 자바(버전 17)를 자신에 맞는 OS에 맞춰 먼저 다운로드 한 후(이미 다운로드한 상태라면 상관없음)  
https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html  

![언어 선택](https://user-images.githubusercontent.com/89377563/151611837-96ef1f2f-736d-4b43-8daa-2d1e89f93110.PNG)    
![자바 버전 선택 및 램 할당](https://user-images.githubusercontent.com/89377563/151612292-d9006af7-a6e9-40a3-ac85-862b04ec43fd.PNG)  
처음 다운로드 받은 MultiMC 파일을 압축 해제 후 실행시킨 후, 사용할 언어를 설정하고 자바 버전 17을 선택한 후 메모리 최소 할당값과 최대 할당값을 높인다.  
권장 램 할당은 5GB(5120MB)이므로 그보다 더 높게 할당해야 원활하게 플레이 할 수 있다.  

![프로필 설정](https://user-images.githubusercontent.com/89377563/151611844-11bb09de-fc0e-4d2f-b647-042eb0a37261.PNG)  
![프로필 설정2](https://user-images.githubusercontent.com/89377563/151611848-fbe4fdf2-ba02-4bf1-beb5-74f0574c0d6f.PNG)  
계정에서 MOJANG 계정 추가에서 본인의 모장 계정을 추가한다.  
  
![인스턴스 추가](https://user-images.githubusercontent.com/89377563/151611857-5c1fe2cb-c71a-4a21-b7d0-cde997a4b8e9.PNG)
![인스턴스 설정](https://user-images.githubusercontent.com/89377563/151612531-cafbe282-8481-4f45-af3f-e9da98213bb2.PNG)
![실행](https://user-images.githubusercontent.com/89377563/151612543-22e48124-a28b-410c-b896-0f7f62321e69.PNG)
![MultiMC 실행확인](https://user-images.githubusercontent.com/89377563/151611891-d7b8515d-5bd5-4950-9f9d-b2702c814572.PNG)
그리고 인스턴스 추가를 눌러 다운로드 받은 모드팩 선택 후(무조건 .zip 형태여야함!!) 약간의 기다림 후 실행시키면 된다.  
  
  
# 2: 직접 파일경로에 찾아서 넣기  
아래에 주어진 두 url을 클릭 후 모두 다운로드 한다. (위는 Fabric Loader, 아래는 모드 파일이다.)  
Fabric Loader: https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.10.2/fabric-installer-0.10.2.exe  
Mods: https://drive.google.com/file/d/1MIHlX3XBjcb9D0nQAYeGXkj_na8DpJEZ/view?usp=sharing (깃헙에는 고용량 파일을 올리기 복잡한 관계로 구글 드라이브로 대체)  
  
![패브릭 설치](https://user-images.githubusercontent.com/89377563/151611973-566099f3-f209-4e76-98c0-3dece7ec20ff.PNG)  
다운로드 한 Fabric Loader.exe를 실행시킨 후 Fabric Loader를 다운로드 할 폴더가 마인크래프트 파일이 설치된 폴더가 맞는지 확인 한 후 다운로드한다.  
  
![초기실행](https://user-images.githubusercontent.com/89377563/151611977-1a82b7a0-c664-42ae-a1e9-1ef963689dda.PNG)  
그리고 마인크래프트 런쳐를 실행시킨다.  
  
![실행확인](https://user-images.githubusercontent.com/89377563/151611989-132600a7-ae42-4f65-8c50-3fa885da4e3b.PNG)  
실행한 후 먼저 한 번 제대로 설치되었는지 Fabric Loader이라 쓰인 파일을 실행시킨다.  

![파일넣기](https://user-images.githubusercontent.com/89377563/151611993-063cba05-b78b-4255-91cc-f5a0251e0b58.PNG)  
제대로 실행이 되는 것을 확인했다면 win+R키(실행)를 눌러서 %appdata%를 입력한 후 .minecraft 폴더에 다운로드한 모드파일을 압축해제 후 붙여넣기 한다.  
  
![실행완료](https://user-images.githubusercontent.com/89377563/151611998-ac212d2d-4b09-49e5-80f8-498b82cac4da.PNG)  
그리고 램을 5GB 이상 적절히 할당 후 실행시키면 된다.  

추가: 마인크래프트 런쳐에서 램 할당 추가로 하는 법: 런쳐를 실행한 후 설치설정 -> 실행할 파일(Fabric Loader-1.18.1)에 커서를 가져다대면 점이 ... 모양으로 3개 있는 박스가 보이는데 그걸 클릭 -> 수정 클릭 -> 아래에 설정 더 보기 클릭 -> JVM 인수에 -Xmx2G라 되어있는 부분의 숫자를 바꾸면 됨. (예를 들어 -Xmx8G라 하면 8기가가 할당됨)
