<template>
  <div class="ct-flex">
    <AddNewUser @click="toggleModal"/>
    <div class="ct-flex-grow">
      <div class="ct-mb-8">
        <ComponentHeader />
      </div>
      <div class="ct-flex ct-justify-end ct-mb-8 ct-mr-4">
        <AddUser />
      </div>
        <ContributionNavbar />
        <AdminTab />
        <p class="ct-p-3 ct-font-bold ct-text-brand-black">CreateTeamListView1</p>
        <VotersTable />
    </div>
  </div>
</template>

<script>
import ComponentHeader from '@/components/ComponentHeader';
import AddUser from '@/components/AddUser';
import ContributionNavbar from '@/components/ContributionNavbar.vue';
import AdminTab from '@/components/AdminTab.vue';
import VotersTable from '@/components/VotersTable.vue';
import AddNewUser from '@/components/AddNewUser.vue';

export default {
    name: 'Home',
    components: {
        ComponentHeader,
        AddUser,
        ContributionNavbar,
        AdminTab,
        VotersTable,
        AddNewUser,
    },

}
</script>

<style scoped>

</style>
