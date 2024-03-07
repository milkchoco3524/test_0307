# test_0307
## 마크다운 기본 명령어
---------------------------

# 1. 제목

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

---------------------------------

# 2. 텍스트 강조

- 굵게: '**텍스트**', '__텍스트__'
- 기울임: '*텍스트*', '_텍스트_'
- 취소선: '~~텍스트~~'

------------------------------------

# 3. 목록

- 순서가 있는 목록
  1. 항목 1
  2. 항목 2
  3. 항목 3
- 순서가 없는 목록
  - 항목 1
  - 항목 2
  - 항목 3
  
-----------------------

# 4. 복사

``` bash
blablablalba
```

-------------------------

# 5. 링크

- 인라인 링크: '[링크 텍스트](링크 URL)'
  [유튜브](https://www.youtube.com/)
- 참조 링크: '[링크 텍스트][링크 참조명]', '[링크 참조명]: 링크 URL'(문서의 다른 곳에 정의된 링크를 참조할 때 사용)

------------------------------

# 6. 코드 블록

- 인라인코드: '코드'
- 코드블록:
  ```언어
  코드 내용
  ```
  
----------------

# 7. 인용문

> 이것은 인용문입니다.
---
# 8. 수평선
'-','*', '_' 기호를 세 번 이상 연속 사용하여 생성

'---'
'***'
'___'

-------------

# 8. 라텍스 수식

1. 인라인 수식: 수식을 문장 중간에 표시하고 달러기호('$')를 수식 앞 뒤로 넣는다.
   예: '$E=mc^2$'

  $E=mc^2$
   
3. 별도 줄에 표시되는 수식: 수식을 별도의 줄에 표시한다. 두개의 달러기호('$$')를 수식 앞 뒤로 넣는다.
   예: $$
       \frac{1}{n}
       $$

       $$
       \frac{1}{n}
       $$
   
   이것은 분수를 표현:1/n
   
---------------

# 9. 테이블

텍스트 기반의 표 제작 가능
| 열 1 제목 | 열 2 제목 |
|------------|-----------|
| 셀 1       | 셀 2      |

----------------

# 10. 체크박스 목록

- [x] 작업 완료
- [ ] 작업 진행 중

-----------------------

# 11. 이모지

:smile: :thumbsup: :rocket:

------------
# 12. 백슬래시 이스케이프

특수문자 표현
특수문자 앞에 백슬래시를 넣으면 특수문자 명령어로 처리 안됨

\*이탤릭체\*

----------------------

# 13. 이미지 삽입

1. 이미지 업로드: GitHub 리포지토리에 이미지 파일을 업로드
   
  - 리포지토리 페이지로 이동
  - 상단의 "Add file" 버튼을 클릭하고 "Upload files"를 선택
  - 이미지 파일을 드래그하여 업로드가능

2. 이미지 삽입: 이미지를 마크다운 문서에 삽입

  - 마크다운 문서에서 이미지를 삽입할 위치로 이동
  - 이미지를 삽입하려는 위치에 이미지 파일의 경로를 입력
    (일반적으로 '/폴더명/이미지파일명.확장자' 형식으로 입력)
    예시: '![대체 텍스트](/images/example.jpg)'
  - 이미지 파일의 경로 대신 웹 상의 이미지 URL을 입력하여 외부 이미지를 삽입할 수도 있다.
    예시: '![대체 텍스트](https://example.com/image.jpg)'

3. 대체 텍스트 추가: 이미지에 대체 텍스트를 추가하는 것이 좋습니다. 대체 텍스트는 이미지가 로드되지 않았을 때 대신 표시되며, 시각 장애인이나 검색 엔진에 의해 사용될 수 있습니다.

---------------------------


