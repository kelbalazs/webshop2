<template>
<v-app>
    <div>

  <div class="search-wrapper">
      <form>
        <div class="search-text-container">
          <input type="text" class="search-bar" v-model="search" placeholder="What are you looking for?" />
        </div>
     
      </form>
    </div>
    <div v-if="categories.length" id=categories>Featured Categories
      <ul class="featured categories">
      <li v-for="(cat, index) in categories" :key="index" class="flex-item">
        <div>
          {{cat.category_name}}
        </div>
 
      </li>
    </ul>
    </div>
</div>
</v-app>

</template>

<script>
import axios from 'axios';

export default {
      data(){
    return{
      categories: [],
      search: '' 
    }
  },
  async mounted(){
    this.categories = 
    (await axios.get(' https://portal.thebuyhive.com/api/ecom/v2/search?keyword=&category=&page=1&sort_by=default')).data.categories
  },

  computed: {
    filteredCategories() {
  return this.categories.filter((cat) => cat.category_name === this.search)
}
  }
}
</script>
