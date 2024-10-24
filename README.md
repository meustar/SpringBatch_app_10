# 2024-10-23
---
#### 키워드
스프링 시큐리티.
인증 / 인가
@Valid 무효성 검사?
csrf 토큰
---

## 2교시
- 37강 스프링 시큐리티, 로그인, 로그아웃, 회원가입 1
- 38강 스프링 시큐리티, 로그인, 로그아웃, 회원가입 2

#### 37강 memberContext는 38강 안에 있음.

#### 38강 layout, sec 해결법
- settings > Inspection 검색 > namespace 검색 > XML Unbound namespace prefix 체크해제.

## 4교시
- 39강. 코드 설명 및 주석.

## 5교시
- 40강 음원 관련 파일 업로드, 테스트
- 41강 음원 관련 페이지, 컨트롤러 테스트

## 6교시
시나리오.
A
- 음원 1
- 음원 2 => 노래 1, 20,000 => 상품 1
- 음원 3
- 음원 4 => 노래 2, 200,000 => 상품 2

B
- 음원 5
- 음원 6 => 노래 3, 10,000 => 상품 3
- 음원 7
- 음원 8 => 노래 4, 150,000 => 상품 4

1. 내 음원은 나만 볼 수 있다.
2. 내 상품은 남들도 볼 수 있다.
3. 본인이 만든 음원을 상품화
  - 내가 만든 상품은 내 장바구니에 담을 수 없다.
  - 색상, 사이즈, 갯수  X
  - Cash 충전금
  - 정산.

이전에 했던 쇼핑몰 내용들 총 동원해서 사용할 계획.

---

# 2024-10-24
---
#### 키워드


---

##  2교시
- 42강 
  - 참고1 [내가 @NoArgsConstructor (access = AccessLevel.PROTECTED)를 작성했던 이유](https://velog.io/@kevin_/%EB%82%B4%EA%B0%80-NoargsConstructor-access-AccessLevel.PROTECTED%EB%A5%BC-%EC%99%9C-%EC%9E%91%EC%84%B1%ED%96%88%EC%9D%84%EA%B9%8C)
  - 참고 2 [[Spring] @Transactional의 이해](https://imiyoungman.tistory.com/9)


시나리오.
회원, 음원 -> 상품 -> 장바구니 -> Cash -> 주문

## 3교시

- 43강 장바구니, Cash 도입

## 4교시

- 44강 주문, 환불 기능 구현.
- 주문 상세보기 