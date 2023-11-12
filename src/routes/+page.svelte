<script>
  import "@shoelace-style/shoelace/dist/themes/light.css";

  import { browser } from "$app/environment";

  // The app breaks when this line is enabled
  // import "@shoelace-style/shoelace/dist/components/button/button.js";

  if (browser) {
    // The app works when this line is enabled
    import("@shoelace-style/shoelace/dist/components/button/button.js");
  }
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>

<sl-button>Hey there</sl-button>
