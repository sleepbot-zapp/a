<nav>
  <ul class="font-black text-base">
    {#each options as option}
      <li>
          <a href="/Spanish">{option}</a>
      </li>
    {/each}
  </ul>
</nav>

<style>
  @import url(https://fonts.googleapis.com/css?family=Open+Sans);

  nav {
    width: 500px;
    mask-image: linear-gradient(90deg, rgba(255, 255, 255, 0) 0%, #271e1e 25%, #e6e6e6 75%, rgba(255, 255, 255, 0) 100%);
    margin: 0 auto;
    padding: 60px 0;
  }

  nav ul {
    text-align: center;
    background: linear-gradient(90deg, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 0.2) 25%, rgba(255, 255, 255, 0.2) 75%, rgba(255, 255, 255, 0) 100%);
    box-shadow: 0 0 25px rgba(0, 0, 0), inset 0 0 1px rgba(255, 255, 255);
  }

  nav ul li {
    display: inline-block;
  }

  nav ul li a {
    padding: 18px;
    font-family: "Open Sans";
    text-transform:uppercase;
    color: rgb(240, 119, 19);
    font-size: 18px;
    text-decoration: none;
    display: block;
  }

  nav ul li a:hover {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1), inset 0 0 1px rgba(219, 114, 114, 0.6);
    color: rgba(0, 35, 122);
  }
</style>

<script>
  let options = ["Spanish Clubs", "English Clubs"]
</script>