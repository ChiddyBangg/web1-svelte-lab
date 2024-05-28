<script>
  export let person;
  ;
</script>

<!-- details of a person-->

<dl>
  <dt>ID:</dt>
  <dd>{person.id}</dd>
  <dt> Name:</dt>
  <dd>{person.name}</dd>
  <dt>Email:</dt>
  <dd>{person.email}</dd>
  <dt>Phone Number:</dt>
  <dd>{person.phone}</dd>
  <dt>location:</dt>
  <dd>{person.address.city}</dd>
  <dt>Website:</dt>
  <dd>{person.website}</dd>
</dl>

<style>
  dl{
    color: white;
  }
</style>
