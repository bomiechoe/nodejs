# nodejs

## 노드 간단하게 살펴보기
### 특징
```
* 비동기 입출력
* 이벤트기반 입출력
* 노드의 모듈
```

### 모듈
코드의 일부를 떼어내어 특정한 기능의 모듈을 만들 수 있다. 사용하고자 하는 경우 require()으로 불러들인다. 불러들인 파일은 자바스크립트 객체로 인식하며, 해당 객체를 참조하여 내부의 기능을 사용한다. 다수의 모듈을 합쳐서 패키지로 생성이 가능하며, 이러한 패키지는 npm 프로그램으로 쉽게 설치하여 사용할 수 있다.

### node 실행 
``` node something.js  ```    
명령 프롬프트 창에서 node.exe 파일을 실행하면서 자바스크립트 파일을 실행하면 해당 파일이 실행된다.    
```node```    
node.exe 파일만 실행하면 노드 shell로 들어가 실행된다.

### 노드의 전역 객체
console : 콘솔창에 결과를 보여주는 객체  
processs : 프로세스에 대한 정보를 다루는 객체  
export : 모듈을 다루는 객체
