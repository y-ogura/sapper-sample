<script context="module">
  export function preload({ query }) {
    return { query }
  }
</script>
<script>
  let name = 'World!'
  export let query
  if (query.name) {
    name = query.name
  }
</script>

<h1>Hello, {name}</h1>