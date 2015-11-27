# bootstrap-wp-nav-walker-updated
How to use

```
$args = array(
								'theme_location' 	=> 'primary',
								'menu' 				=> '',
								'menu_class' 		=> 'menu',
								'menu_id' 			=> '',
								'echo' 				=> true,
								'fallback_cb' 		=> 'wp_page_menu',
								'items_wrap' 		=> '<ul id = "main-nav" class = "nav navbar-nav %2$s">%3$s</ul>',
								'depth' 			=> 0,
								'fallback_cb'       => 'bootstrap_wp_navwalker::fallback',
								'walker'            => new bootstrap_wp_navwalker()
								);

							wp_nav_menu( $args );
```
