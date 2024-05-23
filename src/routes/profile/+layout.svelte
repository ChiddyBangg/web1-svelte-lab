<script>

import Sidebar from "../../Components/Sidebar.svelte";

let nav = [
    { text: "Home", href: "/" },
    { text: "Profile Image ", href: "/profile/profile-image" },
    { text: "Company", href: "/profile/company" },
    {text: "Contact Details", href: "/profile/contact-details"}
    // { text: "Contact", href: "/contact" },
  ];
</script>
<Sidebar navItems={nav} />
<section>
    <slot />
    <h2> all the profile ideas</h2>
</section>




<style>
    section{
       
        background-color: purple;
        border:1px, dashed pink ;
    }

</style>