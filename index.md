# How big is this header
## How big is this header
### How big is this header
#### How big is this header
##### How big is this header
###### How big is this header
![Saul Goodman from the hit TV show 'Better Call Saul'](https://www.meme-arsenal.com/memes/0dad556c3aaa0fb4a164c0a890e3e569.jpg)
``` javascript
function calculateWinner(squares) {
  const lines = [
    [0, 1, 2],
    [3, 4, 5],
    [6, 7, 8],
    [0, 3, 6],
    [1, 4, 7],
    [2, 5, 8],
    [0, 4, 8],
    [2, 4, 6],
  ];
  for (let i = 0; i < lines.length; i++) {
    const [a, b, c] = lines[i];
    if (squares[a] && squares[a] === squares[b] && squares[a] === squares[c]) {
      return squares[a];
    }
  }
  return null;
}
```
