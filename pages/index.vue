<template>
  <section class="container">
    <div>
      <h1 class="title">
        Sun Son
      </h1>
      <h2 class="subtitle">
        Just a word play on <em>Suraj Kumar</em>
      </h2>
      <div class="box">
        <div class="content">
          <p>This website is under rapid re-construction. It is undergoing a profound transformation of a spiritual kind that appears extremely material and utilitarian as a set of software tools and a community of my friends from real life who can do useful things with me - such as schedule my time to learn Transcendental Meditation from me, connect to my diverse set of friends from the <em>alternative</em> community, procure stuff through the informal, but organized network that I run, called <a href="http://green.org.in">GREEN</a>, etc., etc.,.</p>
          <p>Please check back in a day or two.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
.content
{
  margin: 30px;
  background-color: #fcc;
}
</style>
