# 2022 Practice Personal Prj
IntelliJ / JPA / Springboot 연습


--
22.02.10
쿼리에서 ORDER BY - DESC 사용을 할 때,
TO_NUMBER()로 감싸주지 않을 경우
9999 가 10000 보다 큰 수로 인식이 된다.
정렬 할 때, 번호로 사용 할 경우 주의할 것 - 기본적인 것

--
22.02.11
ORDER BY 절에는 FUNCTION 을 사용하는 것을 지양해야하므로
차라리 관련된 다른 컬럼을 기준으로 정렬하는 것이 좋다.
EX - 작성 날짜 REG_DATE
