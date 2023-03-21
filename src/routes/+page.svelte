<script>
  import { todo } from "/src/lib/todo.js";
</script>

<main>
  <h1>Achievement 19</h1>
  <section>
    {#each todo as todo}
      <article class="card">
        <ol>
          <li>{todo.first}</li>
          <li>{todo.second}</li>
          <li>{todo.third}</li>
          <li>{todo.forth}</li>
          <li>{todo.fifth}</li>
          <li>{todo.sixth}</li>
          <li>{todo.seventh}</li>
          <li>{todo.eighth}</li>
        </ol>
      </article>
    {/each}
  </section>
</main>
