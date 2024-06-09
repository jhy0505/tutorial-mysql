# [MySQL] create
### CREATE: 데이터베이스(스키마), 테이블, 인덱스 등을 생성할 때 사용

<br/>

### 데이터베이스(스키마) 생성 기본 구문

```sql
CREATE DATABASE '데이터베이스 명';
```

<br/>

### 데이터베이스(스키마) 생성 예시

```sql
CREATE DATABASE exampleDatabase;
```

<br/>

### 테이블 생성 기본 구문

```sql
CREATE TABLE '테이블 명' (
  '컬럼명1' '타입' '기타옵션',
  '컬럼명2' '타입' '기타옵션',
);
```

<br/>

### 테이블 생성 예시

```sql
CREATE TABLE example_table (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(50) NOT NULL,
  email VARCHAR(100)
);
```