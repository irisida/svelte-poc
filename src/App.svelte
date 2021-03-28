<script>
  import Obj from './components/Obj.svelte';

  import Renderer from './components/Renderer.svelte';

  const content = `# markdown here!
  Here's a **markdown** based post.`;
</script>

<Obj objectId="00000000-0000-0000-0000-00000000" />

<Renderer title="hello" {content} />
