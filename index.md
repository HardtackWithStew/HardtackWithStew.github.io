# 여기 사람있어요(송민재)

# [컨셉]

## 메인컨셉 : 탈출  

- 큰 맵에서 적들을 피해 목표지점까지 이동하는 것이 메인.  
- 도중 전투가 가능하나, 너무 많이 전투를 하면 불이익을 준다.
- 제한된 시야와 광원으로 적들의 위치를 파악하기 어려움.

### 서브 컨셉 1 : 현상금 사냥  

- 게임의 도전요소.  
- 일반 게임 난이도에 비해 어려운 적.  
- 도전에 성공하면 큰 보상을 얻음.  
- 탑다운 슈팅 게임에서 탄막게임을 접목시킴.  

### 서브 컨셉 2 : 노획  

- 적들을 처치하면 얻는 보상.
- 아이템에 따라 당장 사용할 수 있는것, 상점에서 팔 수 있는 것으로 나눔.
- 현상금 사냥 시스템으로 적을 잡았을 때 얻는 아이템은 높은 재화로 바꾸거나 자신이 사용할 수 있음.  

### 서브 컨셉 3 : 하이리스크

- 플레이어의 체력을 토큰으로 바꿈으로써 공격을 받을때마다 한칸씩 줄어듦. 공격을 받는 것 자체가 치명적임.
- 적들은 보통 무리로 다니거나, 연속으로 공격할 수도 있다.
- 캐릭터의 사망시, 가지고 있던 아이템을 모두 잃기 때문에 교전을 피하는 것이 안전함.

### 서브 컨셉 4 : 관리

- 인벤토리는 고유한 무게가 있고, 인벤토리에 아이템을 너무 많이 부여할 시, 인벤토리에 넣을 수 없음.
- 이는 탈출에 성공해 아이템을 저장하는 보관시스템에도 적용됨.
- 탈출 후 상점시스템을 이용할때, 체력토큰의 양을 일시적으로 늘이거나 아이템을 사고파는 등, 캐릭터의 성장이나 상태를 관리할 수 있음.  

### 서브 컨셉 5 : 단기접전  

- 체력토큰을 관리하더라도 체력토큰의 양이 많지 않을 수 있음.
- 전투를 줄이거나, 기습을 하는 등 빠르게 적을 제압하는 것이 중요함.
- 공격 시도시, 랜덤한 확률로 적을 생성함.

<br><br>  

# [관련 이미지 & 동영상]

- 이미지
- 컨셉 맵 이미지  
  ![aaa](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/3597c5dc-4b84-42cf-b187-35302c3556f7)
  <br>
- 컨셉 무게 이미지  
  ![무게](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/69091e74-f130-4048-a5b5-0d26c389419e)
- 컨셉 인벤토리 이미지  
  ![인벤토리 보관UI](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/3eae1bde-7741-48f6-9a83-1991ab26a6ee)
- 컨셉 체력UI 이미지  
  ![체력UI](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/bff0a685-9e15-4c47-a047-14e54c537ef5)
  <br>
- 컨셉 현상금사냥 이미지  
  ![현상금 사냥(보스몹)](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/01c670de-66be-4cc6-820a-4d69312af334)
- 동영상
  [![](./img/그림.png)](https://www.youtube.com/watch?v=5xy4n73WOMM)

<br><br>

# [대표 이미지]

![aaaaaaaa](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/05845ae2-1066-4cd8-806d-869ec08d91c2)


<br><br>

# [컨셉 & 대표이미지 기반 작품묘사]

> ### 대표이미지 기반 :

> ### 컨셉 기반:

<br><br>

# [<여기 사람있어요> 구성 요소]  

- 맵에 고립된 플레이어가 탈출에 성공하면 외치는 구조신호를 제목으로 만들었다.
- 극한의 상황을 연출하여 플레이어로 하여금 이 제목이 생각나게끔 연출하고자 함.

<br>

## 1. 메커니즘

[도전 과제]

1. 제한시간이 지나야 목표지점(탈출지점)을 생성시킴.
2. 적AI들을 제압하거나 눈에 띄지 않게 이동하며 극복한다.
3. 탈출한 사례금 + α(현상금 수거, 적의 아이템 강탈 후 상점시스템에 판매한 재화)를 통해 캐릭터에게 재화를 사용하여 회복/질좋은 아이템 구매하여 다른 맵으로 간다.
4. 다른 맵에 가기 전, 현상금 사냥 이벤트를 통해 강력한 보스몬스터를 소환, 추적, 제거한다.  

[재미 요소]

1. 거대한 맵에 고정적이지 않은 스폰 포인트에서 랜덤으로 살아나기 때문에 전에 탈출한 방식이 아닌 유동적인 방식으로 생존해야한다.
2. 도전과제였던 보스몬스터들은 일반 적들과 달리 탄막공격을 하기때문에 슈팅게임과 더불어 탄막게임을 즐길 수 있다.
3. 적의 공격 하나하나가 체력 토큰을 줄이는 공격이기 때문에 체력관리를 위해 적과 전투를 할지 피해갈지 전략적인 선택 요구할 수 있다.  

<br>

## 2. 이야기

[만들게 된 배경]  
안개 이펙트와 조명 연출을 위해 맵을 어둡게 하는 방법도 연구하고 싶고, 미완성되었던 인벤토리 시스템을 구하는 것 또한 목표다.  

[카메라 관점]  
탑다운 시점. 맵 전체에 안개 이펙트를 넣고, 마우스의 위치에 따라 조명을 밝혀주는 형식으로 시야를 제공한다.  

<br>

## 3. 미적요소

[디자인][컬러]  
도트 그래픽. 숲과 강가, 그 주변의 작은 마을을 배경으로 한다.
하나의 맵으로 진행하며, 탈출에 성공할 경우 주인공이 있는 베이스캠프(숲 속에 차려진 텐트와 사람들이 있는 곳)로 이동한다.  

[음향]  
BGM대신 숲의 벌레소리나 새소리, 바람소리를 차용계획.
총소리, 풀 밟는 소리등으로 이동시 숲을 걷는 느낌을 줄것.

<br>

## 4. 기술

유니티 엔진을 사용한 PC기반의 2D 탑다운 슈팅 게임.

<br> <br>

# [게임 시스템 디자인]
## 1. 게임 오브젝트 분해

|연번|종류|한글 오브젝트|영어오브젝트|사용처|사진|
|:----:|:----:|:----:|:----:|:----:|:----:|
|1|플레이어|플레이어|Player|공용|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/77a7a55c-3a57-4131-897b-02143783ecd5)|
|2|적|들개|dogs|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/987e7682-3e7f-484f-ac71-044c64328fdf)|
|3|적|스캐빈저|HUMANscab|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/7532410b-4a78-4bbf-a7cc-ef08fdad3710)|
|4|적|곰|bear|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/7f1d202d-54eb-40d3-b845-9fe2ae77e972)|
|5|보스|정예투척병|bomber|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/f2259957-7546-4e52-a8b9-f0447181945b)|
|6|보스|정예전투병|gunman|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/1a485641-86de-4f89-ad53-7942f379f2ce)|
|7|상점|상점주인|salesman|베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/a7760760-322b-4b74-b765-d25a72f26191)|
|8|상점|숙소|tent|베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/feba3940-1b7c-4bd6-8d68-2d8d33363850)|
|9|상점|보관함|i_box|베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/f64e6db3-bffb-49fd-ad99-f17003c53e02)|
|10|아이템|압박붕대|bandage|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/1c045c1e-2d08-4cd3-a77d-8a56bdbc457e)|
|11|아이템|통조림|c_food|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/517c1b32-d51c-4718-aded-805c72dc7f2c)|
|12|아이템|수류탄|granade|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/dad690ee-b03a-4243-9815-615a6f58c127)|
|13|아이템|일반탄 |FMJbullet |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/fc0877af-7375-4616-bbb0-3ffb7c21aa8c)|
|14|아이템|할로우포인트|HPbullet |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/ce55ac88-fbc8-4faf-99e5-5c0a3ecd5a8a)|
|15|아이템|벅샷|buckshot|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/824bcd74-82e6-4a8c-a340-b2e3faeac5f2)|
|16|아이템|야생고기|Meat |베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/155e7ce6-f399-4e31-81b8-4bbb3a9406a4)|
|17|아이템|재화|coin |베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/aae237dd-9a90-49e1-bd1c-d314a94a0035)|
|18|무기|권총|pistol|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/b6c8e220-7920-4d5c-9e48-b8140961de3f)|
|19|무기|엽총|rifle|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/e94fac93-5aa8-4909-a041-ed440abb6e41)|
|20|무기|산탄총|shotgun|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/c329333c-8b5e-44ea-b074-8a16e16a73b9)|
|21|무기|자동소총|AR |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/8639f476-31cb-4ebb-b59c-4d8af8840183)|
|22|UI|체력|HP|공용|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/3bfd4fd7-8d0a-4ba0-a64c-978cef4a625c)|
|23|UI|조준점|crosshair |공용|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/b9978a30-3a50-46c8-ab23-2a445eeaf137)|
|24|UI|지도 |PaperMap |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/87be9b73-dc7d-4e3d-93e9-a97fc8175dd3)|
|25|UI|탈출지점|exitPoint |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/c4ec7320-df33-4951-b700-e8030b7f4a1c)|
|26|UI|수류탄|isGranade |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/e12d8da5-6a70-4162-a79c-57fd11081822)|
|27|UI|잔탄|isBullet |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/2f16f819-618b-4c5c-995a-cdb2a10a8df7)|
|28|UI|자본|isCoin|베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/4c64f3fa-834a-448a-9df3-28776bdb9572)|
|29|UI|무게표시|weight |공용|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/c3a540df-e214-42e4-8fad-e580cdb4b163)|
|30|오브젝트|드럼통|GasCan|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/34cfdb7e-b528-46d0-8b71-b52b172176fa)|
|31|오브젝트|아이템생성상자|box |필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/457948f2-c768-4bbe-8644-74a38626c858)|
|32|오브젝트|현상수배|Wanted_D|베이스캠프|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/d57a7509-6309-46bf-a638-639ba667e10c)|
|33|오브젝트|탄환|bulletOut|필드맵|![image](https://github.com/HardtackWithStew/HardtackWithStew.github.io/assets/128970120/d04c0002-2c02-4550-be91-c5754e1d7c83)|

<br> <br>
## 2. 파라미터(속성) 뽑아 보기
<br>

### 1) 오브젝트 이름 : Player

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|체력|hp|플레이어의 체력 수. 토큰형식이므로 100%방식이 아님.||
|이동속도|speed|플레이어의 이동속도.||
|무게|weight|플레이어가 가지고 갈 수 있는 아이템의 무게 총합.||
|수류탄갯수|granadeCount|플레이어가 가지고 있는 수류탄 수.||
|잔탄|bulletCount|플레이어가 가진 총안에 장전되있는 탄약 수.||
|소진|isAmmo|플레이어의 탄창이 비었는지 확인용 속성||
|무리소환|reinforce|랜덤한 확률로 총을 발사할 때 보스가 아닌 몬스터를 생성할 확률||
<br>

### 2) 오브젝트 이름 : HUMANscab, dogs, bear, bomber, gunman

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|체력|animalHP,scabHP,bossHP|적들의 체력. 적들은 체력바로 표기.||
|이동속도|animalSpeed,scabSpeed|적들의 이동속도.||
|데미지|animalDmg,scabDmg,bossDmg|적들의 데미지||
|아이템|Rand_Item|아이템 랜덤 소지||
|잔탄|bulletCount|플레이어가 가진 총안에 장전되있는 탄약 수.||
|감지범위|bustedPoint|적들의 감지범위||
|무리 만들기|swarm|보스가 아닌 같은 종류의 몬스터 랜덤한 숫자로 다중생성||

<br> <br>
## 3. 행동 뽑아 보기
<br>

### 1. 오브젝트 이름 : bomber, gunman
|행동|영문명칭|설명|
|:----:|:----:|:----:|
|정지|IDLES|멈춤. 최초 스폰시 상태|
|식별|isBusted|플레이어 감지 시스템.|
|움직임|randMoving|랜덤 움직임.|
|공격1,2,3|attack1,attack2,attack3|공격패턴|
|사망|isDead|체력이 0이 되었을 때.|

<br>

### 2. 오브젝트 이름 : Player
|행동|영문명칭|설명|
|:----:|:----:|:----:|
|움직임|moving_walk|어떤 방향이든 누르면 움직임|
|달리기|running|shift를 누름으로써 움직임 가속|
|사격|Gunfire|마우스 왼쪽버튼으로 사격|
|수류탄 던지기|GranadeOut|오브젝트 수류탄을 G키로 전방으로 던짐|
|인벤토리 열기/닫기|ShowInv/UnshowInv|E키로 인벤토리 열기/닫기|
|상호작용|getItem|체력이 0 이하가 된 적과 가까이 있을 때 f키로 아이템창 열기/닫기|
|사망|youDie|체력이 0이 될 때 캐릭터 삭제|
|정지|IdleP|정지 상태.|
|재장전|reload|R을 눌렀을 때, 잔탄UI 숫자 감소, 탄창UI숫자 증가 |

<br>

### 3. 오브젝트 이름 : HUMANscab, dogs, bear
|행동|영문명칭|설명|
|:----:|:----:|:----:|
|정지|IDLES|멈춤. 최초 스폰시 상태|
|식별|isBusted|플레이어 감지 시스템.|
|랜덤움직임|randMoving|랜덤 움직임.|
|고정움직임|MovingAtk,scabMoving|플레이어 방향으로 움직임, 스캐빈저는 플레이어와 일정한 거리를 유지하며 움직임|
|공격|sAttack|스캐빈저의 총 발사|
|사망|isDead|체력이 0이 되었을 때.|

<br> <br>
## 4. 상태 뽑아 보기
<br>

### 1. 오브젝트 이름 : Player
|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|정지|움직임|wasd로 움직임.|
|움직임|정지|아무 키도 누르지 않음, 정지|
|움직임|달리기|shift키를 누르는 동안 가속|
|달리기|움직임|shift키를 떼면 가속 중지|
|정지|마우스 클릭|왼쪽 마우스로 탄 발사|
|움직임|마우스 클릭|이동 중 왼쪽 마우스로 탄 발사|
|마우스 클릭|정지|마우스 클릭 중지시, 사격 중지|
|마우스 클릭|움직임|이동중 마우스 클릭 중지시, 사격 중지|
|정지|수류탄|g키로 수류탄 발사 준비|
|움직임|수류탄|g키로 수류탄 발사 준비|
|수류탄|움직임|수류탄 준비 중, 이동|
|수류탄|마우스 클릭|왼쪽 마우스로 수류탄 발사|
|수류탄|수류탄|g키로 수류탄 발사 준비 종료|
|정지|인벤토리 열기|e키로 인벤토리 열기|
|인벤토리 열기|인벤토리 열기|e키로 인벤토리 닫기|
|정지|상호작용|f키로 적과 나의 인벤토리 열기|
|상호작용|상호작용|인벤토리 열기 중, f키로 인벤토리 닫기|
|정지|재장전|r키로 현 탄창 숫자 최대치로 충전|
|움직임|재장전|움직이는 중 r키로 현 탄창 숫자 최대치로 충전|
|사망|사망|체력 토큰이 1보다 없을 경우, 베이스캠프 아이템 저장, 현 플레이어 데이터 삭제, 베이스캠프에서 캐릭터 신규 생성.|

<br>

### 2. 오브젝트 이름 : HUMANscab, bear, dogs
|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|정지|정지|이동 없음|
|정지|랜덤움직임|모든 몹 고정 이동속도로 랜덤 움직임|
|랜덤 움직임|정지|랜덤움직임 종료, 1초 뒤 윗 상태 재돌입|
|정지 |식별|플레이어가 보이지 않는 식별 구역에 들어올 시. |
|랜덤 움직임|식별|움직이는 도중 플레이어가 보이지 않는 식별구역에 들어올 시|
|식별|고정움직임|플레이어 추적, 몬스터가 곰이나 개일 경우, 플레이어와 닿을때까지 추적.|
|고정움직임|랜덤 움직임|플레이어와 충돌했을 경우, 랜덤한 방향으로 움직여 거리를 벌림.|
|고정움직임|공격|몬스터가 스캐빈저 일 때, 거리를 유지하며 총알 발사.|
|사망|사망|몬스터 체력바의 숫자가 1보다 작은 경우, 사망 애니메이션 재생 후, 사망 스프라이트로 전환.|

<br>

### 3. 오브젝트 이름 : bomber, gunman
|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|정지|정지|이동 없음|
|정지 |식별|플레이어가 보이지 않는 식별 구역에 들어올 시. |
|식별|움직임|전투상태 돌입, 적의 체력바 UI 켬, 랜덤하게 움직임.|
|움직임|공격|플레이어와 충돌했을 경우, 랜덤한 방향으로 움직여 거리를 벌림.|
|고정움직임|공격|몬스터가 스캐빈저 일 때, 거리를 유지하며 총알 발사.|
|사망|사망|몬스터 체력바의 숫자가 1보다 작은 경우, 사망 애니메이션 재생 후, 사망 스프라이트로 전환.|

<br> <br>
## 5. 플레이어 캐릭터 속성(파라미터)
<br>

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|AR상태|ARMan|전투소총을 든 상태. 인벤토리에 일반탄이 있어야 사격가능.|마우스를 누르고 있으면 누른만큼 총알이 발사된다.|
|저격상태|RifleMan|소총을 든 상태. 인벤토리에 일반탄이 있어야 사격가능.|한발 한발이 강하다.|
|샷건상태|ShotGunMan|산탄총을 든 상태. 인벤토리에 샷건탄이 있어야 사격가능.|사격시, 탄이 부채꼴로 3개 생성된다.|
|권총상태|PistolMan|권총을 든 상태. 인벤토리에 할로우포인트가 있어야 사격가능.|이동속도가 가장 빠르다.|
|인벤토리에서 각 총기에 해당하는 총기를 장착하면 폼이 바뀐다.
각 탄의 데미지는 1이고, 보스가 아닌 적의 체력은 10이다.
소총은 데미지가 5다.
AR상태가 아니라면 모든 총기는 마우스를 누른 순간 한 개의 잔탄을 소비하며, 자신 앞에 총알을 생성한다.
권총상태는 기본 이동속도가 +5.0f 증가한다.
모든 총알의 속도는 20.0f이고, 저격상태는 40.0f의 속도다.|
