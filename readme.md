# This Project is for  

- This project is for developing together ui for web.
- UI for Mobile device would be developed with another project.

## 프로모션  

- 판매하고는 결이 다름  
- Stepper 방식으로 진행함 (1. 기본정보 입력 2. 정책정의 3. 고객범위 선택 4. 결제  5. 검토)
- 프로모션 타입  
-- 사전판매: 프로모션 등록하면 판매에도 등록되어야 함  
-- 단순홍보: 신제품 등의 단순 홍보목적 프로모션  
-- 할인: 날짜/요일/시간대 할인률 제공 (가격할인 또는 바우처 지금율 상향 등)  

## 사전판매  

- 예약과 사전판매는 다르다  
- 사전판매는 미리 구매 (바우처 또는 카드 등의 결재) 후에 나중에 사용할 수 있다  
- 사전판매 업종은 음식업 등이 해당됨(온라인 쇼핑 등의 업종은 해당 없음)  
- 예약은 업소가 아니라, 개인을 위한 기능?  

## 판매  

- 업소 입장에서의 Voucher 판매는 의미가 없다 (업체 입장에서는 바우처 자체가 현금이기 때문임)  
- 개인은 Voucher 판매가 가능하고 업소에서는 상품판매가 가능하다  
- 종류 
-- 단순판매 (Voucher, 상품 모두 가능)  
-- 경매/역경매 (상품만 가능함)  -> 우선순위 떨어짐  

## 선물/요청

- 특정 사용자를 지정하여 선물함  
-- 상대방이 OK 한 이후에 바우처가 이동함  
- 특정 사용자에게 바우처 선물을 요청함  
-- 상대방이 OK한 이후에 바우처가 이동함  
- 사용자를 선택할 때에 자신의 핸드폰에 등록된 사람을 지정하거나 전화번호를 직접 입력할 수 있음  
-- 핸드폰 앱에 친구 등록 등의 기능이 있어야 함 (WEB에도 마찬가지 임)  
-- 전화번호 입력시 회원등록 여부 확인하여 미등록이면 "불가"를 표시하고 해당 번호에게 선물시도와 회원등록을 유도하는 메시지를 전송함  


## 업소유형

- 업소 유형은 하나로 통일하는 것이 필요해 보임 (이럴 경우 아래 내용 불필요)  
-- 대신 모든 업소에서 2가지 유형의 바우처를 발행할 수 잇도록 함  
-- 동맹가능 바우처, 동맹불가능 바우처  
- 단순  
-- 자신 가게에서 바우처를 발행할 수 있고 다른 가게의 바우처와 호환 불가함. 
-- Deposit 하지 않음 (단순유형 업소 회원에서 발생한 바우처는 현금이 아님)
-- 해당 가게에서만 사용할 수 있음  
- 동맹
-- 모든 가게에서 사용 가능한 바우처를 발행할 수 있음

### 바우처 종류

- 동맹가능 바우처  
-- 발행할 때에 해당 액수만큼 Deposit 해야 함. 대신에 모든 회원 Store에서 사용 가능함  
- 동맹불가 바우처  
-- 발행할 때에 Deposit 불필요함. 대신 본인의 가게에서만 사용할 수 있음  
- 두가지 종류 바우처 모두 판매/선물/요청이 가능함  
  
## 기타

- 업소 입장에서의 Voucher 판매는 의미가 없다 (업체입장에서는 바우처 자체가 현금이기 때문임)
- 판매에는 개인끼리의 Voucher 판매와 업소에서의 상품판매가 있다  
