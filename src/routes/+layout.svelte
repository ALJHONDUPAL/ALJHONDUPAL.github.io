<script lang="ts">

  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>


<Navbar>
	<NavBrand href="/">
	  <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Flowbite</span>
	</NavBrand>
	<NavHamburger  />
	<NavUl >
	  <NavLi href="/">Home</NavLi>
	  <NavLi href="/about">About</NavLi>

	</NavUl>
  </Navbar>