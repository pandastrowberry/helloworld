# helloworld
**git 및 github 공부용

데이터베이스와 테이블의 차이는 무엇인가요?
- 데이터베이스 : 단편적인 정보를 담은 데이터의 저장소
- 테이블 : 데이터를 입력하는 표

MySQL에서 데이터를 조회할 때 사용하는 기본 SQL 명령어를 설명해주세요
SELECT : 데이터를 조회할 테이블의 열 조회
WHERE : 특정 조건에서 데이터 조회
FROM : 조회할 데이터가 있는 테이블 조회
HAVING : 데이터를 특정 조건으로 묶어서 계산한 결과를 출력(GroupBy 다음에 사용)  
JOIN : 두 테이블의 관계를 보고 합쳐서 하나의 결과를 출력 
ORDER BY : 데이터를 오름차순, 내림차순으로 정렬

'Primary Key'와 'Foreign Key'의 차이와 각각의 역할에 대해 설명해주세요.
- Primary Key : 테이블의 행을 구분하는 유일한 열, 반드시 지정되어야 하는 열
- Foreign Key : 다른 테이블의 행에서 여러 값을 참조할 수 있는 열

MySQL에서 'JOIN'이란 무엇이며, 'INNER JOIN'과 'LEFT JOIN'의 차이점은 무엇인가요?
- 연관되어 있는 테이블을 합쳐서 하나의 결과를 나타내는 테이블 통합방법으로 INNER JOIN은 일대다로 연결된 테이블 관계에서 중복되어 있는 값중 고유한 값을 침조하여 합친 결과를 출력하는 방법이고, LEFT JOIN은 값이 있는 테이블에 조건을 걸고 값이 없는 테이블과 합친 결과를 출력하는 방법
  
정규화(Normalization)란 무엇이며, 왜 중요한가요?
- 관계형 데이터베이스를 만들 때 테이블끼리 중복된 데이터를 허용하지 않기 위해 관계를 분해하여 기준을 명확히 정한 뒤 이상현상을 없애 무결성과 정확성이 높아진 관계를 만드는 과정. 
