# Pygame

Welcome to the Pygame wiki!

# Tetromino_Shadow

> Fixer : 2014036871_전자통신공학과_홍순상

- 기본적인 테트리스 코드는 Tetromino를 따라 코딩했습니다.

출처 : https://inventwithpython.com/pygame/chapter7.html

- Tetromino에 Shadow 기능을 넣어, 블럭의 현재 X 위치와 rotation을 동일하게 낙하시켰을 때의 스택 모습을 Shadow로서 보여주는 기능을 구현했습니다.

## Feature List

> 이 탭에서는 Tetromino_Shadow의 기능을 나열합니다.

_1. Music_

- 플레이를 시작할 때, 미리 저장해놓은 오디오 파일을 이용하여 게임 플레이 중의 BGM으로 사용합니다.

_2. Shadow_

- 현재 떨어지고 있는 블럭의 X좌표와 Rotation을 동일하게 한 상태에서 블럭을 낙하시켰을 때, 어떻게 블럭이 쌓이게 될지 미리 보여줍니다.

_3. Pause_

- P를 누르면 현재 진행하고 있는 게임을 일시정지 합니다.

_4. Spin_

- 양방향 회전을 할 수 있습니다. 기본적으로 위 화살표 키를 누르는 방향만으로 회전하면 빠른 쌓기가 불가능 할 수 있으므로 q버튼을 이용하여 반대 방향으로 회전시킬 수 있습니다.

_5. Exit Button_

- 종료 버튼을 제작하여 추가 했습니다. 단축키는 Esc키이며 키보드의 Esc키 위치를 시각화하여 좌측 상단에 위치 시켰습니다.

_6. 화살표 추가기능_

- 위, 아래, 좌우 화살표를 이용하여 추가 기능을 사용할 수 있습니다. 위에서 서술한 것과 같이 위 화살표를 눌렀을 때는 회전이 가능합니다.
- 또한, 좌우 화살표를 눌렀을 때는 블럭의 좌우좌표를 수정시킬 수 있습니다.
- 아래 화살표를 눌렀을 때에는 블럭을 빠르게 낙하시킬 수  있습니다.
- Space 키를 눌렀을 때에는 블럭을 한번에 최하점으로 낙하시킬 수 있습니다.

_7. Next Block_

- 현재 블럭을 쌓은 다음에 나올 블럭을 보여줍니다.
