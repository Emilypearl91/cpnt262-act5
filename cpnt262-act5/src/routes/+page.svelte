<script>
  import Card from "../lib/components/Card.svelte";
</script>
<nav>
  <ul>
     <li><a href="/">Home</a></li>
    <li><a href="/">Blog</a></li>
    <li><a href="/">About Me</a></li>
  </ul>
</nav>

<Card></Card>

<main>
  <footer>
    <ul>
      <li><a href="/">Facebook</a></li>
      <li><a href="/">Instagram</a></li>
      <li><a href="/">Twitter</a></li>
    </ul>
    <p>© 2023 Emily Seafoot</p>
 </footer>
</main>

<style>
  nav{
  height: 3rem;
  background-color: black;
  color: white;
  margin-top: 0;
  
}

nav ul{
  list-style: none;
  display: flex;
  justify-content: center;
  margin: auto;

  background-color: black;

  padding: 0;
  height: 3rem;
  
}

nav li{
  display: inline-block;
  padding: 1rem;
  
}

nav a{
  text-decoration: none; 
  color: white;

}

nav a:hover{
  color: white;
} 

main {
  display: flex;
  flex-direction: column;
  flex: auto;
}

footer {
  padding-top: 2rem;
  height: 3rem;
  margin-top: 3rem;

  background-color: black;
}

footer p {
 margin: auto;
 text-align: center;
 padding-top: 3rem;
}

footer ul {
  list-style: none;
  display: flex;
  justify-content: space-evenly;

  margin: auto;
}

footer a {
  text-decoration: none;
  color: white;
}
</style>
