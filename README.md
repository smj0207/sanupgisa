## 쇼핑몰 사이트만들기 및, 데이터베이스 연결입니다

우선 css,html등을 이용하여 이러한 웹사이트들을 제작해줍니다

![image](https://user-images.githubusercontent.com/97486300/186582398-5d253b05-6b8f-40bd-8710-57c781d94953.png)

그러면 이런 페이지가 나옵니다

![image](https://user-images.githubusercontent.com/97486300/172318216-9123442b-8eaf-4641-9eea-0a564bab282d.png)

이 페이지에서 이렇게 데이터를 넣고 등록을 넣어주면 데이터가 등록이 됩니다

![image](https://user-images.githubusercontent.com/97486300/186582713-9d8d7b10-b47e-43f2-aefc-aec0f8d756e4.png)

아래 코드로 회원이름, 번호,주소,가입일자,고객등급 등을 입력 받습니다

![image](https://user-images.githubusercontent.com/97486300/186583628-7d1db31c-f68c-4dd9-b556-c4537957d8ca.png)

모든 정보를 넣고 등록을 누르면 등록이 됩니다

## 다음은 조회입니다

![image](https://user-images.githubusercontent.com/97486300/172318216-9123442b-8eaf-4641-9eea-0a564bab282d.png)

## 이 페이지에서 조회를 누르면

![image](https://user-images.githubusercontent.com/97486300/186586167-1831ccd5-836d-4cf3-b7b4-f278ce0acf01.png)

요로코롬 데이터베이스에서 연결된 회원의 정보와 함께 제가 등록했던 제 정보가 입력됩니다

## 실행코드입니다

![image](https://user-images.githubusercontent.com/97486300/186588032-3ace7119-ffa0-4f9a-827d-3ae37a61906a.png)

to_char 코드로 날짜데이터를 yyyy-mm-dd 형식으로 변형해줍니다<br>
또한 case문을 사용해 고객등급을 각각 vip, 일반, 직원으로 표시 할 수 있게해줍니다

입력 받고 변형까지 완료된 데이터는

![image](https://user-images.githubusercontent.com/97486300/186589824-ee56ccb1-0e97-488d-a5ea-062e1c9be8fb.png)

rs.getString형식을 사용해 불려옵니다


## 느낀점 <br>
*이해가 많이 부족한거 같습니다..
 그렇기에 설명도 부족하고 코드해석도 힘든거 같습니다
더 정리해보고 이해할려 노력해야할거 같습니다*
