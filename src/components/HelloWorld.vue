<template>
<div>
  <header>Comicomic</header>
  <div class="container">
    <div class="img">
    </div>
    <div style="display:inline-block;">
      <div style="font-size:36px;background:#000;color:#fff;">MY HEXSCHOOL</div>
      <table>
        <tr><td class="first-td">Genres</td><td>Fusce/vehicula/dolor</td></tr>
        <tr><td class="first-td">Author</td><td>Namae Shiranai</td></tr>
        <tr><td class="first-td">Status</td><td>Ongoing</td></tr>
        <tr><td class="first-td">Rate</td><td>
          <span class="fa fa-star"></span>
          <span class="fa fa-star"></span>
          <span class="fa fa-star"></span>
          <span class="fa fa-star"></span>
          <span class="fa fa-star-half"></span></td></tr>
      </table>
      <div style="padding-left:13px;">
      <h3>Summary</h3>
        <p>
        If your banker breaks, you snap;
        if your apothecary by mistake sends you poison in your pills, you die.
        </p>
        <p>
        Therefore, I say, I saw that this situation of mine was the precise situation of
        every mortal that has this Siamese connexion with a plurality of other mortals.
        </p>
      </div>
    </div>

    <div class="title">All Chapters</div>
    <div class="chapters">
      <ul>
        <li>Chapter 1: The F2E Challenge Start!</li>
        <li>Chapter 2: Todo List is Going Crazy!<span class="new">NEW</span></li>
      </ul>
    </div>
  </div>
</div>

</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  color: #50ff44;
  background: #000;
  height: 74px;
  font-size: 36px;
  font-weight: bold;
  line-height: 74px;
  font-style: italic;
  text-align: center;
}
.container {
  width: 70%;
  margin: 0 auto;
  padding: 20px 0;
}
.img {
  display: inline-block;
  width: 292px;
  height: 438px;
  background: url("../assets/cover.png");
  background-size: cover;
  vertical-align: top;
}
table {
  margin-top: 20px;
}
table td {
  padding: 5px 10px;
}
.first-td {
  font-weight: bolder;
}
p {
  white-space: pre-line;
}
.title {
  display: inline-block;
  margin-top: 20px;
  font-size: 24px;
  background: #000;
  color: #fff;
  padding: 5px;
}
.chapters {
  border: 4px solid #000;
  background: #fff;
}
ul {
  padding: 0;
}
ul li {
  padding: 10px 0 10px 20px;
  list-style: none;
  cursor: pointer;
}
ul li:hover {
  background: #000;
  color: #fff;
}
.new {
  color: #000;
  background: #50ff44;
  padding: 3px;
  font-weight: bold;
  margin-left: 20px;
}
</style>
