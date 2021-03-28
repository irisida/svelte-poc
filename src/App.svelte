<script>
  import Obj from './components/Obj.svelte';
  import List from './components/List.svelte';

  import Renderer from './components/Renderer.svelte';
  import ViewAdd from './components/ViewAdd.svelte';

  const date = Date.now() / 1000;

  const content = `# markdown here!
  Here's a **markdown** based post.`;
</script>

<Obj objectId="00000000-0000-0000-0000-00000000" />

<Renderer title="hello" {content} />

<List {date} />

<ViewAdd />
