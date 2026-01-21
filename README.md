# C# Unity Study
C# 유니티 스터디를 정리하기 위한 레포지토리

## 2026-01-10
**start()**: 유니티 엔진이 실행되거나 start 함수가 호출될 때 한 번 실행  
**update()**: 매 프레임마다 실행  
**[SerializeField]**: 유니티 엔진 ui에서 변수 값을 변환할 수 있도록 변수 직렬화를 해주는 명령어  
*Unity 엔진 ui에서 변경한 변수 값은 Script에 변경되지 않음 
**Input.GetAxis()**: Horizontal, Vertical 등의 축을 넣으면 그 축에 대한 입력 값을 변화

**Time.deltaTime**: 프레임 속도와 관계없이 일정한 속도마다 함수가 호출되도록 보정

## 2026-01-11

Cinemachine brain: 여러 개의 카메라를 관리해 어떤 카메라를 사용자에게 보이게 할지 등 다양한 카메라 기능을 관리

Cinemachine camera package: 다양한 기능

Position Control의 다양한 기능

Rotation Control의 다양한 기능

Damping: 카메라가 얼마나 빠르게 쫓아갈지 결정

## 2026-01-12

Rigidbody: component 중 하나, 중력, 질량 등을 설정할 수 있음. constraints를 통해 회전이나 특정 축의 위치를 고정할 수 있음

**1. 게임 실행(Play) 중 컴파일 방지 설정**

게임을 실행할 때마다 또는 실행 중에 코드를 고쳤을 때 갑자기 멈추며 컴파일하는 것을 막는 방법입니다.

1. 유니티 상단 메뉴에서 **Edit > Preferences**를 선택합니다.
2. 왼쪽 탭에서 **General**을 클릭합니다.
3. **Script Changes While Playing** 항목을 찾습니다.
4. 옵션을 `Recompile After Finished Playing`으로 변경합니다.
    - **Recompile And Continue Playing (기본값)**: 재생 중에도 컴파일하고 계속 실행 (중간에 렉이 걸림).
    - **Recompile After Finished Playing**: 게임 재생을 멈춘 후에만 컴파일을 시작합니다. **(추천)**
    - **Stop Playing And Recompile**: 컴파일이 필요하면 아예 게임을 중단시킵니다.

## 2026-01-19

`OnCollisionEnter()` 콜라이더가 겹칠 경우에 작동하는 함수

## 2026-01-20

`GetComponent<>()` <>안에는 어떤 요소를 받아 올 것 인지 작성, 그 후 . 연산자로 세부 요소를 결정 

### Unity Docs

Unity Docs를 잘 활용해서 Unity의 각 기능들을 알아보면 유익함

Time.time 시작 버튼을 누른 후 얼마나 많은 시간이 흘렀는지 초 단위로 나타냄

`tag` 기능을 활용해 다양한 상태를 표현할 수 있음

`transform.Translate` 위치를 변화

`transform.Rotate` 회전

## 2026-01-21

`MoveTowards()`


