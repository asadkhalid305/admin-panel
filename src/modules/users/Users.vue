<template>
	<div class="about-page">
		<ListPageTitle title="Users" create-route="createUser"/>
		<UsersList/>
	</div>
</template>
<script>
  import UsersList from './components/UsersList'
  import ListPageTitle from '../core/components/semantics/ListPageTitle'

  export default {
    name: 'Users',
    components: { ListPageTitle, UsersList }
  }
</script>
