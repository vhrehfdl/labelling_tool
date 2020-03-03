### 환경설정
---
- pip install django~=2.0.0


### 사용법
---

[ 접속 테스트 ]

1. python [manage.py](http://manage.py) runserver 0.0.0.0:8000
2. http://ip주소/polls/project_list
ex) [http://113.142.171.133:8000/polls/project_list](http://115.145.173.133:8000/polls/project_list)
3. 접속 테스트 끝나면 데몬으로 계속 띄워두기

[ 실제 사용 ]

1. nohup python [manage.py](http://manage.py/) runserver 0.0.0.0:8000
2. New Project 클릭 후 새로운 프로젝트 생성

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/07df30fd-bbd5-4085-be39-10241c7489aa/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/07df30fd-bbd5-4085-be39-10241c7489aa/Untitled.png)

3. New Project 들어간 후 아래의 양식을 전부 채워주세요.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1d8b58c2-f881-4f40-8e16-1a0135fa4ad4/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1d8b58c2-f881-4f40-8e16-1a0135fa4ad4/Untitled.png)

    - Project Name : 입력할 때 공백 값 없이 입력해주세요.
    - Image Upload : 이미지 파일 여러개를 한번에 올려주세요.
    - Class : Add 버튼을 눌러 분류하고자 하는 클래스를 입력해주세요.

        ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d1d3980a-d1a0-4503-bd70-a5a4bc583201/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d1d3980a-d1a0-4503-bd70-a5a4bc583201/Untitled.png)

4. Project List에 들어가 이미지 분류하고 업로드 버튼을 눌러주세요. ( 제출 버튼은 다음 페이지로 넘어가기전에 눌러주시면 됩니다. )

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0665ee6a-4fa6-4eb6-8c72-cc6e31e7e142/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0665ee6a-4fa6-4eb6-8c72-cc6e31e7e142/Untitled.png)

5. Project List에 Download 버튼을 누르시면 CSV 파일 결과값을 얻으실 수 있습니다.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/30a8ad52-ffb5-4623-801f-560791c30680/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/30a8ad52-ffb5-4623-801f-560791c30680/Untitled.png)

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3efbd34-27f6-4b22-96e7-010a395dd907/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3efbd34-27f6-4b22-96e7-010a395dd907/Untitled.png)

- 서버 죽이는 방법
- ps -al 명령어를 실행 후 살아있는 데몬 PID를 찾아 KILL을 한다.

### 주의 사항

---

- New Project를 생성할 경우 Project Name은 이전에 생성했던 이름과 중복되지 않아야 합니다.
- 이미지 이름은 가급적 숫자 혹은 영어로 작성해주세요. ( 한글도 상관없으나 깨질 수 있습니다. )
