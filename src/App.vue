<template>
  <div>
    <AppHeader />

    <div class="ui container">
      <router-view />
    </div>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader";

export default {
  name: "App",
  components: { AppHeader }
};
</script>

// Authorization: Client-ID YOUR_CLIENT_ID
// ClientID: b75409208816cc9
// Client Secret: 93aab3e14f91d1f94aa6ac24f75b67e01dfaa2b9
