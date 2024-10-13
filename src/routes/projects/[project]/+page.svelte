<script>
  import { onMount } from "svelte";
  // import { getChantById } from "$lib/firebaseService.js";

  export let data;
  let id = data.work;
  let content = {};
  /**
   * @type {{ title: any; content: any; } | null}
   */
  let chant;

  onMount(async () => {
    // const chantPromise = getChantById("chants", id); // Example usage
    // chant = await getChantById("chants", id);
    // console.log(chant);
  });
</script>
<body class="bg-[#101317] font-lexend">
  <div class="relative px-36">
    <h1 class="text-white text-7xl font-extrabold mt-2">Hello {id}!</h1>
  </div>
</body>
