# Wordpress Snippets 

#### Get the category name in Post 

<code>
<?php $category = get_the_category();
$firstCategory = $category[0]->cat_name; echo $firstCategory;?>
</code>
