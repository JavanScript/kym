<template>
<div class="boobs">
    <ul>
        <li><a href="#">About me</a></li>|
        <li><a href="#">Sample</a></li>|
        <li><a href="#">What is kym?</a></li>
    </ul>
</div>
</template>

<script>
export default {

}
</script>

<style>

ul{
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0;
    color: rgba(52, 52, 52, 0.5)
}
li{
    margin: 0 10px;
}
a{
    text-decoration: none;
    color: #343434
}
@media (min-width: 481px){
  .boobs{
      font-size: 18px;
  }
}
</style>