# [rsschool-cv](https://groot-0320.github.io/rsschool-cv/cv)

# Aliaksei Kochatau

---

## Contact information:

**City:** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Minsk<br/>
**Phone:** &nbsp;&nbsp;+375 44 728 61 98<br/>
**E-mail:** &nbsp;&nbsp;7286198@gmail.

---

## About Myself:

I started my IT career as a system administrator.
Designed, implemented and maintained corporate network data systems.
Then I got interested in web development.

I used to work as a back-end developer, but then I realized that I was more interested
in front-end development.

## My strengths:

- i can listen and hear the interlocutor
- work under pressure and to tight deadlines
- quickly fit into any existing team of developers
- work closely with other developers
- a disciplined approach to web development projects
- i can and love work on your own with minimum supervision

## Code example:

#### kata from CODEWARS:

*Create a method each_cons that accepts a list and a number n, and returns cascading
subsets of the list of size n*

```
function eachCons(array, n){
  const res = [];
  for(let i = 0; i <= array.length - n; i++){
    const chunk = [];
    for(let j = i; j < i + n; j++){
      chunk.push(array[j])
    }
   res.push(chunk);
  }
  return res;
}
```
### from React component:

```
const Home = () => {
  return (
    <div className="wrapper">
      <h1 style={{margin: '25px 0'}}>Home page</h1>
       <div className="home">
         {GAMES.map(game =>
           <GameItem game={game} key={game.id}/>
         )}
       </div>
    </div>
  );
};

```


