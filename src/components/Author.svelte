<script lang="ts">
  export let author: string;
  export let size = 24;
</script>

<a href="https://github.com/{author}" target="_blank">
  <img width={size} height={size} src="https://github.com/{author}.png?size={size}" alt="" />
  {author}
</a>

<style>
  a {
    display: flex;
    bottom: 0;
  }
</style>
