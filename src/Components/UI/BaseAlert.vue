<template>
 <div class="alert">
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span>
    <slot>
    </slot>
</div> 
</template>

<style lang="postcss" scoped>
 /* The alert message box */
.alert {
  padding: 20px;
  background-color: #DEA5A4; /* Red */
  color: white;
  margin-bottom: 15px;
  border-radius: 0;
}

/* The close button */
.closebtn {
  margin-left: 15px;
  color: white;
  font-weight: bold;
  float: right;
  font-size: 22px;
  line-height: 20px;
  cursor: pointer;
  transition: 0.3s;
}

/* When moving the mouse over the close button */
.closebtn:hover {
  color: black;
} 
</style>