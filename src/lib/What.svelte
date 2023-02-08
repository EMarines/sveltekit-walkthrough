<script>
    import Button from '../lib/button.svelte';
    import Contact from '$lib/Contact.svelte'
</script>
<div class="container grid">
    <div class="what">
        <h3>What We Do</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione id odio quasi quos, vitae sit dolore, libero magnam eaque inventore quas officia rem. Error qui fugit officia amet laboriosam at eos officiis in optio voluptatum.
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque ut, eius illo pariatur voluptate nobis nostrum perspiciatis eaque doloribus neque dolorem. Harum, possimus! Laborum, magnam ducimus cumque temporibus at, voluptatem expedita tempora facilis exercitationem odio impedit natus? Tempore, sapiente inventore.
        </p>

        <Button class = "secondary" id = "a-botton" size = "medium">
            Call To Action >>>
        </Button>
    </div>
 <Contact />
</div>



<style>
    .grid{
        display: grid;
        grid-template-columns: repeat(12, 1fr);
        gap: 2em;
    }
    .what{
        grid-column: span 8;
    }
    
    h3{
        padding-bottom: 0.5em;
        margin-bottom: 0.5em;
        font-size: 2em;
        font-weight: 500;
        border-bottom: 1px solid #ddd;
    }

</style>