<script>
  let title = 'Aelins favorite park';
  let description = 'Aelins favorite park is Elliston park, because she gets to play with a bunch of friends in the off leash area.';
</script>

<a href="https://www.calgary.ca/parks/elliston-park.html">
  <article>
    <h1>{title}</h1>
    <p>{description}</p>
    <img src="src/lib/image/aelin-on-walk.jpeg" alt="black and tan king charles with silver jacket out on a walk">
    <p>click to learn more about Elliston Park </p>
  </article>
</a>

<style>
  article{
margin: auto;
margin-top: 3rem;
padding: 1rem;

max-width:40ch;
border-radius: 1rem;

background-color: hsl(129, 28%, 24%);
color: hsl(141, 17%, 71%);
position: relative;

text-align: center;
}

article:hover{
background-color: hsl(141, 17%, 71%);
color: hsl(106, 28%, 24%);
}

img {
  max-height: 300px;
}

a {
  text-decoration: none; 
}

</style>