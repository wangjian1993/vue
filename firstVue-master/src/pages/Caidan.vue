<template>
	<div class="caidan">
		<caidan-header></caidan-header>
		<ul>
			<book-list
					 v-for="item in books"  
                    :book_name="item.book_name"  
                    :book_munu="item.book_munu"
                    :book_pirck="item.book_pirck">
			</book-list>
		</ul>
		<home-footer></home-footer>
	</div>
</template>
<style scoped>
	.caidan{
		background: #FFFFFF;
	}
	ul{
		padding-bottom: 1.06rem;
	}
</style>
<script>
	// 导入要用到的子组件
	import CaidanHeader from '../components/CaidanHeader'
	import HomeFooter from '../components/HomeFooter'
	import BookList from '../components/BookList'

	export default {  
        data () {  
            return {  
                books: [  
                    { book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},  
                    { book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},  
                    { book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},  
                    { book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},    
                    { book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},  
                    { book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},  
                  	{ book_name: "哈哈哈", book_munu: "呵呵" ,book_pirck:"12"},  
                ]  
            }  
        },  
	// 在components字段中，包含导入的子组件
		components: {
			CaidanHeader,
			BookList,
			HomeFooter
		}
	}
</script>