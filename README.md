# PasswordValidator
비밀번호 유효성 검사

---
- build tool (Gradle)
- 자바 단위 테스팅 프레임워크 (JUnit5)
- 테스트 코드 가독성을 높여주는 자바 라이브러리 (AssertJ)

# 요구사항
- 비밀번호는 최소 8자 아싱 12자 이하여야 한다. 
- 비밀번호가 8자 미만 또는 12자 초과인 경우 IllegalArgumentException 예외를 발생시킨다. 
- 경계 조건에 대해 테스트 코드를 작성해야 한다. 

# 학습한 점 
- @Parameterized, @ValueSource를 활용한 테스트 코드 작성
- 상위 인터페이스를 활용해 random으로 생성되는 비밀번호를 유효한 범위 내의 비밀번호로 생성되도록 코드 작성
