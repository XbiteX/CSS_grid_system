<script>
    import FirstComponent from "$lib/first_component.svelte";
    import SecondComponent from "$lib/second_component.svelte";
    import ThirdComponent from "$lib/third_component.svelte";
    import ForthComponent from "$lib/forth_component.svelte";
    import FifthComponent from "$lib/fifth_component.svelte";
    import SixthComponent from "$lib/sixth_component.svelte";
    import SeventhComponent from "$lib/seventh_component.svelte";
    </script>

<style>

        
    .contenitore {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh; /* Ensure the container takes up the full viewport height */
    }

    .griglia {
        display: grid;
        gap: 30px;
        grid-template-columns: repeat(4, 1fr);
        width: 60%;
        height: 80vh;
    }
</style>

<div class="contenitore">
    <div class="griglia">
        <FirstComponent />
        <SecondComponent />
        <ThirdComponent />
        <ForthComponent />
        <FifthComponent />
        <SixthComponent />
        <SeventhComponent />
    </div>
</div>