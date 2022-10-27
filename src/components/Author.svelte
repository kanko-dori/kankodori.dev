<script lang="ts">
  export let author: string;
</script>

<a href="https://github.com/{author}" target="_blank">
  <img width={24} height={24} src="https://github.com/{author}.png?size=24" alt="" />
  {author}
</a>

<style>
  a {
    display: flex;
    padding-top: 0.5em;
  }
</style>
