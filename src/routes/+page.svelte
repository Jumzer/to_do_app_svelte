<script>
  import AddTodoSection from "./../lib/store/components/todo/AddTodoSection.svelte";
  import TodoSection from "../lib/store/components/todo/TodoSection.svelte";
</script>

<div
  class="min-h-screen bg-olive-one p-0 selection:bg-green-two md:px-8 md:py-24"
>
  <main
    class="mx-auto min-h-screen max-w-none rounded-none bg-cream-four px-5 py-10 outline-none md:min-h-max md:max-w-[60rem] md:rounded-2xl md:px-8 md:outline md:outline-4 md:outline-offset-8 md:outline-cream-four"
  >
    <h1 class="text-2xl font-bold text-gray-three">Tableau de bord</h1>
    <div class="mt-10">
      <AddTodoSection />
      <TodoSection />
    </div>
  </main>
</div>
