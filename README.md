# Django 기본

### MVT 구조

| 구분       | 설명                                      |
| -------- | --------------------------------------- |
| Template | 응답 결과를 시각화해 클라이언트에 보낼 때 쓰는 HTML 템플릿입니다. |
| View     | 요청을 받아 비즈니스 로직을 처리하고 응답을 반환하는 역할을 합니다.  |
| Model    | DB에 대한 정의와 설정을 담아둔 클래스입니다.              |



### MVT 구현 절차

<details>

<summary>1. 프로젝트 구조화</summary>

먼저 디렉토리와 파일 구조를 잡습니다.

</details>

<details>

<summary>2. 모델 추가</summary>

그 다음 DB 테이블을 정의합니다.

</details>

<details>

<summary>3. 뷰URL 매핑</summary>

urls.py 파일 안에서 뷰와 URL의 관계를 설정합니다.

</details>

<details>

<summary>4. 템플릿 작성</summary>

페이지 및 UI를 작성합니다.

</details>

<details>

<summary>5. 뷰에 비즈니스 로직 작성</summary>

요청을 처리해 원하는 응답을 내놓는 비즈니스 로직을 뷰에 작성합니다.

</details>
