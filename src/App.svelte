<script>
  export let name;
</script>

<style>
  table {
    text-align: center;
  }
  td {
		border: 1px solid gray;
    width: 200px;
    height: 200px;
	}
  th {
    background-color: antiquewhite;
  }
</style>

<div>
  <main>
    <table>
      <tr>
        <td style="border-color: transparent;"></td>
        <th scope="col">URGENT</th>
        <th scope="col">NOT URGENT</th>
      </tr>
      <tr>
        <th scope="row">IMPORTANT</th>
        <td>John Lennon</td>
        <td>Rhythm Guitar</td>
      </tr>
      <tr>
        <th scope="row">NOT IMPORTANT</th>
        <td>Paul McCartney</td>
        <td>Bass</td>
      </tr>
    </table>
  </main>
</div>
