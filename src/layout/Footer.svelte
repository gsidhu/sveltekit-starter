<script>
	let date = new Date();
	let year = date.getFullYear()
</script>

<footer class="footer mt-auto">
	<section class="col-6 mx-auto p-3 text-center">
		<nav class="footer-links">
			<a class="footer-social-links link-dark text-decoration-none fs-4" href="https://github.com/gsidhu/sveltekit-starter" target="_blank" rel="noreferrer">
				<i class="bi bi-github"></i>
			</a>
		</nav>
		<div class="copyright-footer">
			<span class="copyright-year"><i class="bi bi-cc-circle"></i> {year}</span>
			<a href="https://thatgurjot.com" target="_blank" rel="noreferrer" class="text-dark">Gurjot</a>
		</div>
	</section>
</footer>