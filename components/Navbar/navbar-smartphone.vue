<template>
    <div>

        <ul class="list-navbar">
             <li><a href="#">hello</a></li>
             <li><a href="#">News</a></li>
             <li><a href="#">Contact</a></li>
             <li><a href="#">About</a></li>
             
        </ul>


    </div>
</template>

<style scoped>

.list-navbar{
  list-style-type: none;
  margin: 0;
  padding: 0;
  background-color: #333;
  overflow: hidden;
}

.list-navbar li a{
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.list-navbar li a:hover{
  background-color: #ddd;
  color: black;
}

</style>