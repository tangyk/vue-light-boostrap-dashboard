<template>
  <div class="content">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12">
          <p>
            <a
              class="btn btn-primary"
              data-toggle="collapse"
              href="#collapseExample"
              role="button"
              aria-expanded="false"
              aria-controls="collapseExample"
            >Link with href</a>
            <button
              class="btn btn-primary"
              type="button"
              data-toggle="collapse"
              data-target="#collapseExample"
              aria-expanded="false"
              aria-controls="collapseExample"
            >Button with data-target</button>
          </p>
          <div class="collapse" id="collapseExample">
            <div
              class="card card-body"
            >Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.</div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-8">
          <edit-profile-form></edit-profile-form>
        </div>
        <div class="col-md-4">
          <user-card></user-card>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import EditProfileForm from "./UserProfile/EditProfileForm.vue";
import UserCard from "./UserProfile/UserCard.vue";

export default {
  components: {
    EditProfileForm,
    UserCard,
  },
};
</script>
<style>
</style>
