<template>
  <div class="card">
    <form>
      <div class="form-group">
        <label for="exampleInputEmail1" class="string">Email address</label>
        <input
          type="email"
          class="form-control"
          id="exampleInputEmail1"
          aria-describedby="emailHelp"
          placeholder="Enter email"
        >
        <small
          id="emailHelp"
          class="form-text text-muted"
        >We'll never share your email with anyone else.</small>
      </div>
      <div class="form-group">
        <label for="exampleInputPassword1" class="string">Password</label>
        <input
          type="password"
          class="form-control"
          id="exampleInputPassword1"
          placeholder="Password"
        >
      </div>
      <div class="form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">Check me out</label>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.card {
  padding: 20px 60px;
}
</style>
