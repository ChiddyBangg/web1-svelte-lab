<script>

    let articles = [
    {
        slug: "cats",
        title: "cats are the internet",
        body: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus facere odit est voluptate beatae nam iure quisquam obcaecati officia repellat, nulla quo similique. Temporibus expedita provident assumenda velit! Mollitia, eaque."
    },
    {
    slug: "Breakfast",
        title: "Breakfast are the internet",
        body: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus facere odit est voluptate beatae nam iure quisquam obcaecati officia repellat, nulla quo similique. Temporibus expedita provident assumenda velit! Mollitia, eaque."
    }
    ]
</script>

<h1>My blog page</h1>
<ul>
    {#each articles as article }
    <li><a href="/blog/{article.slug}">{article.title}</a></li>
{/each}
</ul>


<style></style>