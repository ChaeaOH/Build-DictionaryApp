
# 💻Build A Dictionary App
JavaScript기반의 영어 사전 앱으로 검색된 단어의 발음 기호,발음 소리재생,뜻,예시,동의어를 구현하였습니다. 


# 🔍Detail
- `fetch()`를 사용해 dictionary api 에 요청을 보내 받은 object를 통해서 검색어를 인수로 전달해 data함수를 호출하여 `innerText`속성으로 렌더링 된 단어 사전의 의미와 예시를 제공합니다.
- if문을 통해 검색한 단어가 사전에 없다면  `innerHTML`프로퍼티를 사용해 안내 메세지를 출력합니다.
- data함수에서 새 audio 객체를 만들고 audio src를 전달하여  `audio.play()`메소드를 사용하여 검색한 단어의 url을 통해 발음을 재생합니다.

# 🚀Result
![function](/dictionary.gif)


# 💡Review

- `fetch()` 를 통해 첫번째 인자로 URL, 두번째 인자로 옵션 객체를 받고, Promise 타입의 객체를 반환하는 방법을 적용하는 방법을 익혔다.
- 처음으로 Audio 객체를 생성하고, play() 메소드를 사용해서 음악을 재생하는 방법을 배웠다.
