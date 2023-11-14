# rtan-shop-Dungeon
기존 파일에서 상점기능 및 던전기능  츄거
--
상점
-아이템(판매,구매)기능 추가
---
사용한 함수,문법
1.클래스 및 객체 (Class and Object):
Character 및 Item 클래스: 게임 캐릭터와 아이템을 나타내는 클래스 정의.
player 객체: Character 클래스의 인스턴스로, 게임 플레이어를 나타냄.
inventory 및 shopInventory: Item 클래스의 리스트로, 인벤토리와 상점 아이템 목록을 나타냄.
---
2.열거형 (Enum):
ItemType 열거형: 아이템의 타입을 정의하는 열거형.
---
3.메서드 (Method):
GameDataSetting(): 게임 초기 데이터 설정.
DisplayGameIntro(): 게임 시작 화면 표시 및 플레이어 입력 처리.
DisplayMyInfo(): 플레이어의 상태 정보 표시 화면.
DisplayInventory(): 인벤토리 표시 화면.
DisplayShop(): 상점 표시 화면.
기타 아이템 구매, 판매, 장착, 장착 해제 등을 다루는 메서드들.
---
4.속성 (Property):
Character 및 Item 클래스의 속성: 객체의 속성을 나타냄
---
5.리스트 (List):
inventory 및 shopInventory: 아이템을 담는 리스트.
---
6.조건문 (Conditional Statements):
if, else, switch: 조건에 따른 분기 처리.
---
7.반복문 (Loop):
foreach: 컬렉션(리스트)의 각 요소에 대한 반복.
---
8.입출력 (Input/Output):
Console.WriteLine(), Console.Clear(): 콘솔에 출력하고 화면을 지우는 메서드.
---
9.사용자 입력 처리:
Console.ReadLine(): 콘솔에서 사용자의 입력을 받음.
int.TryParse(): 문자열을 정수로 변환하는 메서드.
---
10.컬렉션 조작:
리스트에 아이템 추가, 삭제 등을 통한 인벤토리 및 상점 아이템 관리.
---
11.메서드 호출:
메서드 호출을 통한 다른 메뉴로의 이동 및 특정 행동 수행.
---
12.플래그 변수 활용:
shopMenuEnabled 변수를 통해 상점 메뉴의 활성화 여부 관리.
---
13.던전 진행:
EnterDungeon 메서드에서는 플레이어가 선택한 던전의 난이도에 따라 던전을 진행합니다.
방어력이 낮으면 던전 실패 확률이 있고, 클리어하면 보상을 받습니다.
---
14.랜덤 값 활용:
Random 클래스를 사용하여 여러 곳에서 랜덤 값을 생성하여 게임의 다양한 요소에 활용합니다.
---



