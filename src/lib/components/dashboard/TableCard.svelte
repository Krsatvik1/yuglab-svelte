<script>
    export let data = [];
  </script>
  
  <div class="...">
    <table class="...">
      <thead>
        <tr>
          <th class="...">Header 1</th>
          <th class="...">Header 2</th>
          <th class="...">Header 3</th>
        </tr>
      </thead>
      <tbody>
        {#each data as item (item.id)}
          <tr>
            <td class="...">{item.field1}</td>
            <td class="...">{item.field2}</td>
            <td class="...">{item.field3}</td>
          </tr>
        {/each}
      </tbody>
    </table>
  </div>