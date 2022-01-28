# 모드 팩 설치 하는 법
모드팩은 버전 1.18.1 기준
두 가지 방법이 있음.


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
  
처음 다운로드 받은 MultiMC 파일을 압축 해제 후 실행시킨 후, 사용할 언어를 설정하고 자바 버전 17을 선택한 후 메모리 최소 할당값과 최대 할당값을 높인다.  
권장 램 할당은 5GB(5120MB)이므로 그보다 더 높게 할당해야 원활하게 플레이 할 수 있다.  
  
계정에서 MOJANG 계정 추가에서 본인의 모장 계정을 추가한 후 인스턴스 추가를 눌러 다운로드 받은 모드팩 선택 후(무조건 .zip 형태여야함!!) 약간의 기다림 후 실행시키면 된다.  
  
  
# 2: 직접 파일경로에 찾아서 넣기  
아래에 주어진 두 url을 클릭 후 모두 다운로드 한다. (위는 Fabric Loader, 아래는 모드 파일이다.)  
Fabric Loader: https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.10.2/fabric-installer-0.10.2.exe  
Mods: https://drive.google.com/file/d/1MIHlX3XBjcb9D0nQAYeGXkj_na8DpJEZ/view?usp=sharing (깃헙에는 고용량 파일을 올리기 복잡한 관계로 구글 드라이브로 대체)  
  
다운로드 한 Fabric Loader.exe를 실행시킨 후 Fabric Loader를 다운로드 할 폴더가 마인크래프트 파일이 설치된 폴더가 맞는지 확인 한 후 다운로드한다.  
그리고 마인크래프트 런쳐를 실행시킨다.  

실행한 후 먼저 한 번 제대로 설치되었는지 Fabric Loader이라 쓰인 파일을 실행시킨다.  
제대로 실행이 되는 것을 확인했다면 win+R키(실행)를 눌러서 %appdata%를 입력한 후 .minecraft 폴더에 다운로드한 모드파일을 붙여넣기 한다. 그리고 램을 5GB 이상 적절히 할당 후 실행시키면 된다.  
