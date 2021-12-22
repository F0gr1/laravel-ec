 <template>
     <div class="container-fluid bg-secondary mb-3">
         <div class="container">
             <nav class="navbar navbar-dark">
                 <span class="navbar-brand mb-0 h1 text-info">Album</span>
                 <div>
                     <router-link v-bind:to="{name: 'picture.list'}">
                      <button class="btn btn-outline-info ">List</button>
                      </router-link>
                     <button class="btn btn-outline-info">ADD</button>
                 </div>
             </nav>
         </div>
     </div>
 </template>
 
 <script>
     export default {}
</script>