# What is Sequential File?

# Stream File

### Stream File의 종류

+ 순차 접근 스트림 파일(Sequential Access Stream File)
+ 임의 접근 스트림 파일(Random Access Stream File)

### 파일 접근 모드(Access Mode) - OPEN

### 파일 접근 모드(Access Mode) - Write

### 파일 접근 모드(Access Mode) - Read

### 파일 접근 모드(Access Mode) - Close

### Random Access Stream File

+ fseek()
+ ftell()
+ Streamfp = fopen("streamfile", "r")
	+ 파일이 열리면 읽기 위치 인덱스는 첫 번째 바이트를 가리키게 설정

# Types of Sequential Files

### 입력 순차 파일(Entry-Sequenced File)

+ 로그 파일과 같은 용도에 많이 사용됩니다.
#### 삽입(Insertion)

#### 검색(Search)

#### 삭제(Deletion)

#### 변경(Modification)

#### 사용 예시

---
### 키 순차 파일(Key-Sequenced File)

#### Key-Sequenced File의 정렬 순서

#### 순차 파일의 특징

### 일괄처리(Batch Processing)



# Sequential File의 설계 및 생성

### Record내의 Data Field의 배치

### Key Field는 무엇으로?

### 적정 Blocking Factor는 얼마여야 할까?

# Sequential File Modification

### 순차 파일에서의 검색(Search In Sequential Files)

### Query

### 삽입(Insertion)

### 삭제(Deletion)

### 수정(Update)

### Modification Transaction을 Transaction File에 모아서 일괄 처리

### Key Sequenced File로 되어 있는 Master File의 Update작업

### Key Sequenced File로 되어 있는 Master File의 Modification작업


