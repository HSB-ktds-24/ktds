# String 메서드
![image](https://github.com/user-attachments/assets/00c966e4-8ad6-4d98-87a9-e1ebe343703e)


# 정규표현식
- ' ^ ': ~으로 시작됨 --> 그룹 지정자 안에 있을때는 !의 의미를 지닌다
- ' [ ] ': 내부에 지정된 문자 중 한글자, 그룹지정자
- ' + ': 지정된 문자중 1글자 이상 반복
- ' $ ': ~으로 끝난다
- 예시
  + boolean isEng = word.matches("^[A-Z]+$");
  + boolean isKor = word.matches("^[가-힣]+$");
  + boolean isNum = word.matches("^[0-9]+$"); 
