<script>
  import Renderer from './components/Renderer.svelte';

  const content = `# markdown here!
  Here's a **markdown** based post.`;
</script>

<Renderer title="hello" {content} />
