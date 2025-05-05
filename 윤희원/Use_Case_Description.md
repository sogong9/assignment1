### 회원 가입

| Actor Action | System Response|
| - | - |
| 1. 사용자가 ID, 비밀번호, 전화번호, 결제 수단, 선호 자전거 유형을 입력한뒤 가입 버튼을 클릭한다. | 2. 회원 정보를 저장하고 가입 완료 메시지를 표시한다. |
| **Alternative courses**| Step 2. 필수 정보 누락 시 오류 메시지를 표시하고 입력을 유도한다. <br> Step 2. ID 중복 시 중복 경고 메시지를 표시한다. |
|**Extensions**|없음|

<br>

---

### 회원 탈퇴

| Actor Action | System Response |
| - | - |
| 1. 사용자가 홈 화면에서 회원 탈퇴 메뉴를 클릭한다. | 2. 탈퇴 확인 메시지를 표시한다. |
| 3. 사용자가 '예' 버튼을 클릭하여 의사를 확정한다. | 4. 해당 회원 정보를 삭제하고 탈퇴 완료 메시지를 표시한다. |
| **Alternative courses** | Step 3. 사용자가 '취소'를 클릭하면 탈퇴 절차를 종료하고 이전 화면으로 돌아간다. |
| **Extensions** |없음|

<br>

---

### 로그인

| Actor Action | System Response |
| - | - |
| 1. 사용자가 로그인 화면에 ID와 비밀번호를 입력한 뒤 로그인 버튼을 클릭한다. | 2. 회원 계정일 경우 일반 사용자 메인 화면으로 이동,<br>관리자 계정(ID: admin, PW: admin)일 경우 관리자 전용 화면으로 이동한다. |                                                                 
| **Alternative courses**| Step 2.로그인 실패 시 오류 메시지를 출력한다 |
|**Extensions** |없음|

<br>

---

### 요금 조회

| Actor Action | System Response |
| -| - |
| 1. 사용자가 요금 조회 메뉴를 클릭한다. | 2. 최근 이용 내역과 각 이용에 대한 요금 정보를 표시한다. |
| **Alternative courses** | 없음 |
| **Extensions** |없음|

<br>

---