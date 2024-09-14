개인 프로젝트 Undead Survivor (2024.2) -> 2주정도 소요

유니티를 처음 써보는 상황이어서, 게임을 만들면서 익혀보자는 생각에 

<https://www.youtube.com/watch?v=MmW166cHj54&list=PLO-mt5Iu5TeZF8xMHqtT_DhAPKmjF6i3x>

- 골드메탈 언데드 서바이버 강좌
  
를 보고, 따라해보면서 게임을 만들어봤다. 시작은 "SampleScene" Scene 부터 시작하면 된다.

게임 개발 자체를 처음해보는 것이어서 어렵고 힘든 부분이 많았지만, 그만큼 배워가는 부분이 정말 많았다.

- 전체적인 유니티의 작동 방식(씬, 애니메이터, 게임 오브젝트등의 기본적인 내용부터 스크립트와 기본함수(update 등), 물리 법칙(rigidbody, collider 등), 빌드 등등)을 배웠다.

밑에서 부터는 유용하게 쓴 중요한 방식들이다.

- 캐릭터와 맵의 x,y 좌표차를 각각 비교해 맵을 옮겨줌으로써 무한 맵을 만드는 로직
 
- pixel perfect camera를 이용한 픽셀 사이사이 빈 공간 맞춤
  
- 오브젝트 풀링 방식을 사용한 오브젝트 동적 생성
  
- 기능별 Manager 클래스를 활용한 유지보수 직관성
  
- 코루틴을 활용한 시간 차 함수 호출 방식
  
- 유니티 에디터의 메뉴를 통해 새로운 사용자 설정 객체를 만들 수 있는 CreateAssetMenu와 ScriptableObject의 활용.
