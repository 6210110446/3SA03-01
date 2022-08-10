
## Installation

ทำการแก้ไข word เป็น 1234 ใน App.js

```sh
<WordCard value="1234"/>
```

แก้ game logic ใน WordCard.js ให้ count attempt เมื่อทายผิด
```sh
console.log('reset')
console.log(state.attempt)
setState({...state, guess: '', attempt: state.attempt + 1})
```


แก้ game logic ใน WordCard.js ให้แสดง attempt count  เมื่อชนะ
```sh

console.log('yeah!')
console.log('Complate in '+state.attempt+' try')
setState({...state, guess: '', completed: true})
```
