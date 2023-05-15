<script>
    import { onMount } from 'svelte';
    import { goto } from '$app/navigation';
    import { session } from '$app/stores';
    import SideNav from './SideNav.svelte';
    import TableCard from './TableCard.svelte';
  
    let data = [];

    const fetchData = async () => {
      const response = await fetch('http://localhost:3111');
      data = await response.json();
    };
  
  </script>
  
  <div class="...">
    <SideNav />
    <TableCard {data} />
  </div>
  