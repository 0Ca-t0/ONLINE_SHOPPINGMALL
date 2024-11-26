# 🎸 _NakWon_ _Online_Shoppingmall
``Flutter`` 를 기반으로 한 온라인 음반 거래 애플리케이션 입니다.

## 💡 프로젝트 소개
### ⏱️ 프로젝트 기간
``2024. 11. 21 - 2024. 11. 27``

### 👥개발 멤버
- 박채은 : 상품 상세 페이지
- 차부곤 : 홈 페이지
- 추수현 : 구매 목록 페이지
- 홍의정 : 상품 등록 페이지
- 황성필 : 장바구니 페이지

### 디렉토리 구조
<details>
  <summary> (Click!)디렉토리 구조 </summary>
  📦lib  
 ┣ 📂pages  
  
 ┃ ┣ 📂cart  (장바구니 페이지)  
 ┃ ┃ ┣ 📜shopping_cart_Page.dart  
 ┃ ┃ ┗ 📜shopping_cart_Page_List.dart  
 ┃ ┣ 📂detail  (상품 상세 페이지)  
 ┃ ┃ ┣ 📂widgets  
 ┃ ┃ ┃ ┗ 📜detail_image_box.dart  
 ┃ ┃ ┗ 📜detail_page.dart  
 ┃ ┣ 📂home  (홈 페이지)  
 ┃ ┃ ┣ 📂widgets  
 ┃ ┃ ┃ ┗ 📜image_box.dart  
 ┃ ┃ ┣ 📜home_page.dart  
 ┃ ┃ ┗ 📜home_page_List.dart  
 ┃ ┣ 📂order  (구매 목록 페이지)  
 ┃ ┃ ┣ 📂widgets  
 ┃ ┃ ┃ ┗ 📜order_box.dart  
 ┃ ┃ ┣ 📜my_orders_page.dart  
 ┃ ┃ ┗ 📜saved_order.dart  
 ┃ ┗ 📂regist  (상품 등록 페이지)  
 ┃ ┃ ┣ 📂widgets  
 ┃ ┃ ┃ ┣ 📜background_photo.dart  
 ┃ ┃ ┃ ┣ 📜info_textField.dart  
 ┃ ┃ ┃ ┣ 📜jaket_photo_button.dart  
 ┃ ┃ ┃ ┗ 📜regist_button.dart  
 ┃ ┃ ┗ 📜regist_page.dart  
 ┣ 📜album.dart  
 ┣ 📜main.dart  
 ┗ 📜theme.dart  
</details>

## 💡 어떻게 사용하나요?
![search](https://velog.velcdn.com/images/utiranoj/post/ef3708f9-176e-4784-bfb5-116dddf78904/image.gif)
![regist](https://velog.velcdn.com/images/utiranoj/post/bbc27b9b-d492-43c9-afa7-a94cb6d01283/image.gif)
![order](https://velog.velcdn.com/images/utiranoj/post/dfd57efc-d41a-4a86-b8ed-f0bf23e5f7f8/image.gif)

- 홈 페이지에서 문자열을 통해 상품을 **검색**할 수 있습니다.
- 각 상품을 클릭하면 상세 페이지로 이동합니다. 해당 페이지에서 정보를 열람하거나 **장바구니에 추가**할 수 있습니다.
- 장바구니에서는 **상품의 수량을 조절**하거나 특정 상품을 삭제한 뒤 구매를 진행할 수 있습니다.
- 장바구니에서 상품을 구매하면 자동으로 구매 목록 페이지로 전환됩니다. **구매한 상품 목록**을 살펴보세요.
- 홈 화면 우측 하단의 ``+`` 버튼을 클릭하여 **사이드 메뉴**를 열 수 있습니다.
  - 상품 등록 : 이미지와 정보를 업로드하여 **새로운 상품을 등록**합니다. 이 때 가격 란에는 숫자만 입력할 수 있습니다.
  - 구매 목록 : 구매 목록 페이지로 이동합니다.
