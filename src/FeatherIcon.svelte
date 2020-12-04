<span>{@html svg}</span>

<script>
	import * as feather from 'feather-icons';

	export let icon, attrs = undefined;
	let svg;
	$: svg = icon ? feather.icons[icon].toSvg(attrs) : '';
</script>
