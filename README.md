# xylophone

* Flutter Study
  - Stateless Widget
    - 상태 관리가 필요 없을 때 사용 
    - 개발 초기에 간단하게 시작하고 개발 중 상태 관리가 필요하면 유연하게 StateFul로 전환가능
  - StateFul Widget
    - 비동기 처리, 상태 관리를 위해서는 StateFul Widget을 사용한다.
    - initState, didUpdateWidget, dispose 등의 lifecycle 메서드를 가진다.
    - setState() 메서드를 호출하면 상태변경, UI를 다시 그리도록 build 메서드를 호출하게되고 변경된 상태를 반영한다.
 - Custom Widget
   - Container를 Root로 사용해서 개발 가능하고 필요한 인자를 받게 하여 커스텀한다.
 - Flutter AudioPlayer Library
   - SoundPool, JustAudio 등 여러 Library가 있고 SoundPool은 현재 지원이 중단됨.
   - JustAudio의 경우 각 AudioPlayer에 음원을 set해주기 때문에 동시에 여러 음원을 재생할 수 도 있다.
  
---
### 위에 정렬된 내용을 사용하여 실로폰 기능을 제공하는 Android, iOS, Web Flutter App Study
- [참고 강의](https://www.inflearn.com/course/플러터-초입문-왕초보/dashboard)
