## 1. branch 생성 및 md file 생성
  branch 이름 : 본인 학과  
  branch에서 따로 생성한 md file 이름 : 본인 학과_intro.md  
intro 뒤에 .md를 붙이지 않으면 # 등의 기호가 처리되지 않고 그대로 노출되므로 file 이름 설정 시 .md를 붙여주세요.
서론 파트 맡으시는 분은 branch 이름을 서론으로 설정, 따로 md file을 만들지 말고 처음 branch 생성 후 나타나는 README.md 파일에서 그대로 작업해주세요. 

## 2. md file 내용 작성
  서론 이외의 각 md file 별로 단락(문단) 구성은 다음과 같습니다.  
* 본인이 정한 기술의 개념 소개
* 등장 배경 
* 핵심 메커니즘
* 응용 분야
* 전망 (혹은 한계점)  

/ 약 200자씩 고르게 해도 좋지만, 핵심 메커니즘 등이 분량이 더 필요하다면 논의 하에 바꿉시다. /    

각 문단은 번호 매기기로 구분합니다.  
가장 첫 줄은 '#. (본인 학과) / (기술 이름)'으로 설정, 본문 작성까지 한 줄을 띄우고, 위의 다섯 문단을 작성합니다.   

  
## 3. 공통적인 commit change 기준 및 양식
  먼저 위의 1번을 모두 수행했을 때 commit change 한 번, commit message는 (본인 학과) branch 및 md file 생성 (서론 제외), extended description은 특별히 추가하지 않아도 됩니다.    
  
  md file 내용 작성 시 

## 4. pull request 기준
  위의 2번에서 설정한 단락 하나를 완성할 때마다 main으로 pull request - 병합은 Merge Commit으로 합니다. 
