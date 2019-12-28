<script>
  export let buah;
  export let sayuran;
  let nama = "hello<b>dunia</b>";
  let angka = 0;

  function tambahsatu() {
    angka = angka + 1;
  }
</script>

<p>
  {@html nama}
</p>

<h1>{angka} {buah} {sayuran}</h1>
<button on:click={tambahsatu}>click</button>
