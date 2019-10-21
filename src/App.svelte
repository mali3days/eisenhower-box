<script>
  export let name;
</script>

<style>
  table {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  td {
		border: 1px solid gray;
    width: 200px;
    height: 200px;
	}
  th {
    background-color: antiquewhite;
  }
  .top-left-block {
    width: 50px !important;
    height: 50px !important;
    border-color: transparent;
  }
  .rotate {
    transform: rotate(-90deg)
  }
  .matrix-body:hover {
    /* TODO: WIP */
    transform: scale(2);
    background: rgb(152, 205, 96);
    z-index: 334232;
  }
</style>

<div>
  <main>
    <table>
      <tr>
        <td class="top-left-block"></td>
        <th scope="col">
          <div>Urgent</div>
        </th>
        <th scope="col">
          <div>Less urgent</div>
        </th>
      </tr>
      <tr>
        <th scope="row">
          <div class="rotate">Important</div>
        </th>
        <td class="matrix-body">
          <div>(Do first)</div>
          John Lennon
        </td>
        <td>
          <div>(Schedule)</div>
          Rhythm Guitar
        </td>
      </tr>
      <tr>
        <th scope="row">
          <div class="rotate">Less important</div>
        </th>
        <td>
          <div>(Delegate)</div>
          Paul McCartney
        </td>
        <td>
          <div>(Don't do)</div>
          Bass
        </td>
      </tr>
    </table>
  </main>
</div>
