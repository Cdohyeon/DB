# DB 
<div align="center">
    <br/>
    <br/>
    <img src="https://github.com/Cdohyeon/DB/blob/main/20171006_015055.png?raw=true" alt="DB" />
    <br/>
    <br/>
    <h3>🍹 데이터베이스</h3>
    <br/>
    <br/>
</div>
<div><h3>데이터베이스란 무엇인가?</div>

정의:
여러 사람이 공유하여 사용할 목적으로 체계화해 통합, 관리하는 데이터의 집합이다. 작성된 목록으로써 여러 응용 시스템들의 통합된 정보들을 저장하여 운영할 수 있는 공용 데이터들의 묶음이다

특징:
1. 실시간 접근성

수시적이고 비정형적인 질의(조회)에 대하여 실시간 처리 응답이 가능해야 한다.

 

 

2. 계속적인 변화

새로운 데이터의 삽입, 삭제, 갱신으로 항상 최신의 데이터를 유지해야 한다

 

3. 동시 공용 

여러 사용자가 동시에 자기가 원하는 데이터를 이용할 수 있어야 한다

 

4. 내용에 의한 참조

데이터베이스에 있는 데이터를 참조할 때 데이터 레코드의 주소나 위치에 의해서가 아니라, 사용자가 요구하는 데이터 내용으로 데이터를 찾는다

장점:
1. 데이터의 중복을 피할 수 있다

2. 저장된 자료를 공동으로 이용할 수 있다

3. 데이터의 일관성과 무결성을 유지할 수 있다

4. 데이터의 논리적, 물리적 독립성이 보장되낟

5. 보안을 유지할 수 있다

6. 데이터를 표준화할 수 있다

7. 데이터를 통합하여 관리할 수 있다

8. 항상 최신의 데이터를 유지한다

9. 데이터의 실시간 처리가 가능하다

단점:
1. 데이터베이스 전문가가 부족하다

2. 전산화 비용이 증가한다

3. 대용량 디스크로의 집중적인 Access로 Overhead가 발생한다

4. 파일의 백업과 회복이 어렵다

5. 시스템이 복잡하다

<div><h3>DMBS란 무엇인가</div>

DMBS=database management system

정의:
다수의 사용자들이 데이터베이스 내의 데이터를 접근할 수 있도록 해주는 소프트웨어 도구의 집합이다

기능:
1. 정의(Definition)기능

모든 응용 프로그램들이 요구하는 데이터 구조를 지원하기 위해 데이터베이스에 저장될 데이터의 형(Type)과 구조에 대한 정의, 이용 방식, 제약 조건 등을 명시하는 기능이

데이터와 데이터의 관계를 명확하게 명세할 수 있어야 하며 원하는 데이터 연산은 무엇이든 명세할 수 있어야 한다



2. 조작(Manipulation)기능 : 데이터 검색 갱신 삽입 삭제 등을 체계적으로 처리하기 위해 사용자와 데이터베이스 사이의 인터페이스 수단을 제공하는 기능이다



3. 제어(Control)기능 : 데이터베이스를 접근하는 갱신 삽입 삭제 작업이 정확하게 수행되어 데이터의 무결성이 유지되도록 해야한다

정당한 사용자가 허가된 데이터만 접근할 수 있도록 보안을 유지하고 권한을 검사할 수 있어야한다

여러 사용자가 데이터베이스를 동시에 접근하여 데이터를 처리할 때 처리결과가 항상 정확성을 유지하도록 병행제어(Concurrency Control)을 할 수 있어야 한다

종류:
<div>
<h3>오라클</h3>
<img src="https://github.com/Cdohyeon/DB/blob/main/1.jpg?raw=true" alt="DB" />
<br>
<h3>mysql</h3>
<img src="https://github.com/Cdohyeon/DB/blob/main/2.jpg?raw=true" alt="DB" />
<br>
<h3>microsoft SQL Server</h3>
<img src="https://github.com/Cdohyeon/DB/blob/main/3.png?raw=true" alt="DB" />
</div>

<div><h3>SQL이란 무엇인가</h3></div>
정의:
관계형 데이터베이스 관리 시스템(RDBMS)의 데이터를 관리하기 위해 설계된 특수 목적의 프로그래밍 언어이다

명령어:
SELECT * FROM 테이블명 WHERE 필드='조건' AND 필드2='조건2'

DELETE FROM 테이블명 WHERE 조건

UPDATE 테이블명 SET 필드='값', 필드2='값', 필드3='값' WHERE 필드 LIKE '조건'

INSERT INTO 테이블명(필드1, 필드2) VALUES ('값', '값' );

CREATE TABLE 테이블명 (

      필드명 타입 조건,


)

연산자:
산술연산자:+,-,*,/,%
비교연산자 : >, >=, <, <=, =, <>(not equal)
논리 연산자:
ALL	ALL=연산자는 하나의 값을 다른 값들의 집합의 모든 값들과 비교할 때 사용합니다.
<table>
<tr>
<td>연산자
</td>
<td>설명
</td>
</tr>
<tr>
<td>+
</td>
<td>더하기 - 연산자 양쪽의 값을 서로 더합니다.
</td>
</tr>
<tr>
<td>-
</td>
<td>빼기 - 오른쪽의 피연산자에서 왼쪽 피연산자를 뺍니다.
</td>
</tr>
<tr>
<td>*
</td>
<td>곱하기 - 연산자 양쪽의 여러 개의 값을 곱합니다. 
</td>
</tr>
<tr>
<td>/
</td>
<td>나누기 - 왼쪽의 피연산자를 오른쪽 피연산자로 나눕니다.
</td>
</tr>
<tr>
<td>%
</td>
<td>나머지 연산(모듈로) - 왼쪽의 피연산자를 오른쪽 피연산자로 나눈 나머지를 반환합니다.
</td>
</tr>
</table>

<table>
<tr>
<td>연산자
</td>
<td>설명
</td>
</tr>
<tr>
<td>=
</td>
<td>두 피연산자가 서로 같은 값인지 아닌지 확인합니다. 같으면 참(true)이됩니다.
</td>
</tr>
<tr>
<td>!=
</td>
<td>두 피연산자가 서로 같은 값인지 아닌지 확인합니다. 서로 다른 값이면 참이 됩니다.
</td>
</tr>
<tr>
<td><>
</td>
<td>두 피연산자가 서로 같은 값인지 아닌지 확인합니다. 서로 다른 값이면 참이 됩니다.
</td>
</tr>
<tr>
<td>>
</td>
<td>왼쪽 피연산자의 값이 오른쪽 피연산자의 값보다 큰지 확인합니다. 크면 해당 조건은 참이 됩니다.
</td>
</tr>
<tr>
<td><
</td>
<td>왼쪽 피연산자의 값이 오른쪽 피연산자의 값보다 작은지를 확인합니다. 작으면 해당 조건은 참이 됩니다.
</td>
</tr>
<tr>
<td>>=
</td>
<td>왼쪽 피연산자의 값이 오른쪽 피연산자의 값보다 크거나 같은지를 확인합니다. 맞으면 조건은 참이 됩니다.
</td>
</tr>
<tr>
<td><=
</td>
<td>왼쪽 피연산자의 값이 오른쪽 피연산자의 값보다 작거나 같은지를 확인합니다. 맞으면 조건은 참이 됩니다.
</td>
</tr>
<tr>
<td>!<
</td>
<td>왼쪽 피연산자의 값이 오른쪽 피연산자의 값보다 작지 않은지를 확인합니다. 맞으면 조건은 참이됩니다.
</td>
</tr>
<tr>
<td>!>
</td>
<td>왼쪽 피연산자의 값이 오른쪽 피연산자의 값보다 크지 않은지를 확인합니다. 맞으면 조건은 참이됩니다.
</td>
</tr>
</table>
<table>
<tr>
<td>ALL
</td>
<td>ALL 연산자는 하나의 값을 다른 값들의 집합의 모든 값들과 비교할 때 사용합니다.
</td>
</tr>
<tr>
<td>AND
</td>
<td>AND 연산자는 SQL 문의 WHERE 절에 여러 개의 조건이 존재할 수 있게 해줍니다.
</td>
</tr>
<tr>
<td>ANY
</td>
<td>ANY 연산자는 조건을 따르는 목록에 해당하는 값을 비교하기 위해 사용됩니다.
</td>
</tr>
<tr>
<td>BETWEEN
</td>
<td>BETWEEN 연산자는 최소값과 최대값을 지정한 값의 범위 내에 있는 값들을 검색하기 위해 사용됩니다.
</td>
</tr>
<tr>
<td>EXISTS
</td>
<td>EXISTS 연산자는 특정한 기준으로 구체화한 테이블에서 행이 존재하는지를 찾기 위해 사용됩니다.
</td>
</tr>
<tr>
<td>IN
</td>
<td>IN 연산자는 어떤 값을 구체화된 리터럴 값의 목록과 비교하기 위해 사용됩니다.
</td>
</tr>
<tr>
<td>LIKE
</td>
<td>LIKE 연산자는 와일드카드 연산자를 사용하여 해당 값과 유사한 값을 찾으려 할 때 사용됩니다.
</td>
</tr>
<tr>
<td>NOT
</td>
<td>NOT 연산자는 사용하려는 논리 연산자의 의미를 반전시킵니다. 사용 예: NOT EXISTS, NOT BETWEEN, NOT IN 등. 이 연산자가 부정 연산자입니다.
</td>
</tr>
<tr>
<td>OR
</td>
<td>OR 연산자는 SQL 문의 WHERE 절에서 여러 조건을 합치기 위해 사용됩니다.
</td>
</tr>
<tr>
<td>IS NULL
</td>
<td>NULL 연산자는 해당 값을 NULL 값과 비교할 때 사용됩니다.
</td>
</tr>
<tr>
<td>UNIQUE
</td>
<td>UNIQUE 연산자는 유일성을 가지도록 구체화된 테이블의 모든 행을 검색합니다. (중복 불허)
</td>
</tr>
</table>


 



