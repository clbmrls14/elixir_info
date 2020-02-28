<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>
      A powerful, functional language that anyone can use.
    </h3>

    <img alt="infographic" class="infographic" src="../assets/infographic.png" />

    <div class="tan_border">
    <h2>Why use Elixir?</h2>
      <ul>
        <li class="info-text">
          Hundreds of companies use Elixir for its scalability and fault-tolerance. Elixir code runs 
          inside lightweight execution threads that allow many processes to be run currently and efficiently.
        </li>
        <li class="info-text">
          Companies like Pinterest and WhatsApp have found great success using Elixir to handle 10 
          times the amount of traffic using half the servers. Now with the Pheonix framework for web 
          development, you build entire web applications in Elixir.
        </li>
        <li class="info-text">
          Elixir has the powerful benefits of running on the Erlang VM, with many modern features 
          common to modern languages.
        </li>
        <br>
        <li>
          <img class="thumb" alt="Pinterest logo" src="../assets/pinterest_logo.png" />
          <img class="thumb" alt="Pheonix logo" src="../assets/phoenix_logo.png" />
          <img class="thumb" alt="WhatsApp logo" src="../assets/whatsapp_logo.png" />
        </li>
      </ul>
    </div>

    <div class="erlang">
      <h2>Built on Erlang</h2>
      <h3>What is Erlang?</h3>
      <p class="info-text">
        <img class="big_img" alt="Erlang logo" src="../assets/erlang_logo.png" />
        Erlang is a functional programming language used to build massively scalable, highly available 
        real-time applications. Erlang was developed as a way to manage telecom systems to ensure that 
        processes could be independent of each other. This meant the system could be handle a huge 
        amount of calls, and an error in a single call wouldn't interfere with any other calls. Elixir 
        was built on the Erlang VM.
      </p>
      <br>
      <p class="info-text">
        Because of it's close relationship with Erlang, Elixir has the benefits of being a nine-nines 
        language, powerful, easily distributable, and scalable. 
      </p>
      <p class="info-text"><a href="https://www.erlang.org/">Learn more about Erlang</a></p>
    </div>

    <div class="tan_border">
      <h2>Scalability</h2>
      <img class="snippet" alt="code to spawn a process" src="../assets/elixir_process.png" />
      <p class="info-text snippet-text">
        Elixir makes it easy to spin up lightweight, isolated processes that can run concurrently. 
      </p>
      <h2>Fault-Tolerance</h2>
      <img class="snippet" alt="code to spawn a process" src="../assets/elixir_error.png" />
      <p class="info-text snippet-text">
        Coping with failure is nobody’s favorite part of programming, but Elixir makes it easy. 
        Elixir is a nine-nines language, meaning it’s easy to have only milliseconds of downtime per year!
      </p>
      <h2>Functional Programming</h2>
      <img class="snippet" alt="code to spawn a process" src="../assets/elixir_functional.png" />
      <p class="info-text snippet-text">
        It’s not always easy to get used to functional programming, but once you master it, your life 
        will change forever. Elixir is great for students or veterans of functional programming alike.
      </p>
    </div>
    <div class="erlang">
      <h2>Want to Learn More?</h2>
      <h3>Visit <a href="https://elixir-lang.org/">elixir-lang.org</a> to learn more</h3>
      <p class="info-text">
        With a growing community and plenty of excellent resources to learn from, there’s no better time 
        to pick up Elixir. Use it to gain an advantage over your competition before it explodes!
      </p>
      <h3>Also check out...</h3>
      <ul>
        <li class="info-text"><a href="https://thinkingelixir.com/">thinkingelixir.com</a></li>
        <li class="info-text"><a href="https://hexdocs.pm/elixir/Kernel.html">hexdocs.pm/elixir</a></li>
        <li class="info-text"><a href="https://github.com/elixir-lang/elixir">github.com/elixir-lang/elixir</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutElixir',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* h3 {
  margin: 40px 0 0;
  padding: 1em;
} */
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  padding: 0.5em;
  text-align: left;
}
a {
  color: #AD7FB4;
}
a:hover {
  color: #6C4C4B;
}
div {
  word-wrap: normal break-word;
  margin: 1em;
  padding: 0.25em 1em 1em 1em;
  border-radius: 15px;
  vertical-align: top;
  overflow: auto;
}

.info-text {
  font-size: 16pt;
  text-align: center;
}
.tan_border {
  background-color: #DAD2BF;
}
.thumb {
  width: 100px;
  height: 100px;
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: cover;
  padding: 1em 2em 0em 2em;
  border-radius: 15px;
}
.erlang {
  text-align: left;
}
.big_img {
  padding-left:1em;
  display: block;
  float: right;
}
.snippet {
  border-radius: 15px;
}
.snippet-text {
   margin: 0.5em 4em 2em 4em;
 }
</style>
