# noCommitNoPhone

너의 커밋이 너의 휴대폰 사용을 자유롭게 하리라

firebase를 통한 github 로그인 및 사용자명 따오기

Github API를 사용한 레포지토리의 커밋 감시

사용하지 못하는 시작 시간을 컨트롤

시간은 하루로 고정. ( 구현이 되고 나면 해당 시간은 설정 가능하게 변경 )

Service를 통해 잠금화면처럼 맨 처음 뜨면서 아예 건드려서 없앨 수 없는 화면을 만들고

화면의 Button을 누르면 해당 시각에 맞는 Commit이 있는지 확인.
있으면 Service 강제 종료 후 설정 시각이 되면 다시 Service 실행.