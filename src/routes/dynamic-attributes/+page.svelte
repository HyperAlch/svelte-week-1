<script>
	let img_src = 'https://svelte.dev/tutorial/image.gif';
	let name = 'Rick Astley';

	// let image2 = {
	// 	src: 'https://svelte.dev/tutorial/image.gif',
	// 	width: 100,
	// 	height: 100
	// }

	// function return_50() {
	// 	return 50
	// }

	// function add_50(x) {
	// 	return x + 50
	// }
</script>

<img src={img_src} alt="{name} dancing">

<br><br>

<!-- <img src={image2.src} width="{image2.width}" height="{image2.height + 200}" alt="{name} dancing"> -->

<br><br>

<!-- <img src={image2.src} width="{return_50() + 100}" height="{add_50(100)}" alt="{name} dancing"> -->

<br><br>

<!-- <img src={image2.src + "lets_break_this_image_path"} alt="{name} dancing"> -->