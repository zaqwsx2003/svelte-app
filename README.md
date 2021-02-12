---

# Svelte app
이 프로젝트는 Svelte를 사용하였습니다.
사용 템플릿은 https://github.com/Rich-Harris/degit 기반으로 만들었습니다.
```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*이 프로젝트를 시작할려면 [Node.js](https://nodejs.org) 다운로드 해야합니다.*


## 시작 방법

종속성 설치!

```bash
cd svelte-app
npm install
```
아래는 다시 실행 하는 방법입니다.
```bash
cd svelte-app
npm run dev
```

[localhost:5000](http://localhost:5000)로 이동합니다.  

---
사용자가 처음 실행하면 아래 사진과 같이 나옵니다.
![1](https://user-images.githubusercontent.com/47521211/107756444-91cb2200-6d67-11eb-9952-edbbc1ad499c.PNG)
---
---
입력창에 텍스트를 입력하면 새 할일 항목이 추가 할 수 있습니다.
![엔터](https://user-images.githubusercontent.com/47521211/107757870-76611680-6d69-11eb-93ab-fecf6b449b5c.PNG)
---
---
Enter 키를 눌러 다음 스크린 샷에서 볼수 있듯이 목록에 새 항목을 추가 할 수 있습니다.
![엔터 다음](https://user-images.githubusercontent.com/47521211/107757877-782ada00-6d69-11eb-8dc3-97b265a40ed9.PNG)
---
---
각 할 일 항목에는 할 일 텍스트 정보 앞에 체크 박스가 있습니다. 
확인란을 사용하여 각 할 일 항목의 완료 상태를 전환이 가능합니다.
체크 박스를 활성화하여 할 일 항목이 완료된 것으로 표시되면 해당 할 일 텍스트에 줄이 그어져 있습니다.
![오늘 할일 쳌](https://user-images.githubusercontent.com/47521211/107757887-79f49d80-6d69-11eb-81b5-8166084615a1.PNG)
---
---
사용자는 왼쪽 하단에 있는 3개의 버튼을 사용하여 항목 목록에 필터를 적용 할수 있습니다.
예를 들어 버튼을 클릭하면 활성상태가 아닌 작업 항목 만 표시하는 목록에 필터가 적용됩니다.
![active필터링](https://user-images.githubusercontent.com/47521211/107757889-79f49d80-6d69-11eb-9ced-5146291f9ba3.PNG)
---
---
이미 완료된 상태에 있는 할  일 항목만 표시하는 필터를 적용 할수 있습니다.
![체크된거확인](https://user-images.githubusercontent.com/47521211/107757891-7a8d3400-6d69-11eb-8857-c2d825bcc808.PNG)
---
---
모두 선택 확인란을 클릭하면 모든 할 일 항목을 한 번에 완료하도록 설정할 수 있습니다.
![다확인](https://user-images.githubusercontent.com/47521211/107757894-7a8d3400-6d69-11eb-8ed1-8ba802210fd4.PNG)
---

```
애플리케이션은 목록에서 할 일 항목을 삭제하는 두 가지 옵션을 제공합니다.

    의 사용하십시오. x 목록에서 단일 할 일 항목을 삭제하려면 오른쪽 아이콘을
    버튼을 사용 Clear Completed 하여 지금 완료된 상태에있는 모든 할일 항목을 한 번에 제거합니다. 
 
```
