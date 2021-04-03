<template>
	<!-- eslint-disable max-len -->
	<div class="container has-text-left">
		<h2 class="subtitle">
			What is chibisafe?
		</h2>
		<h2 class='subtitle'>What is chibisafe?</h2>
		<article class="message">
			<div class="message-body">
				chibisafe is an easy to use, open source and completely free file upload service. We accept your files, photos, documents, anything, and give you back a shareable link for you to send to others. Its source code is available <a href="https://github.com/hifumi-eu/chibisafe" target="_blank">here</a>. 
			</div>
		</article>

		<h2 class='subtitle'>Where is this hosted?</h2>
		<article class="message">
			<div class="message-body">
				This instance of chibisafe is hosted by <a href="https://hifumi.eu" target="_blank">hifumi.eu</a>. It is hosted at <a href="https://www.hetzner.com/" target="_blank">Hetzner Online GmbH</a> in Germany. This means the German laws apply to all the content hosted here.
			</div>
		</article>

		<h2 class='subtitle'>Are my files stored forever?</h2>
		<article class="message">
			<div class="message-body">
				Althrough we can't guarantee files are stored forever, we do not delete them over a given period of time. When logged in you, can delete your own files at any time in your <a href="/dashboard">dashboard</a>. Content can also be deleted by legal means, if necessary.
			</div>
		</article>

		<h2 class='subtitle'>Are my files safe?</h2>
		<article class="message">
			<div class="message-body">
				While will not seek any files, administrators still have a way of accessing them, mostly for legal reasons. This service is subject to our <a href="https://hifumi.eu/privacy.html" target="_blank">Privacy Policy</a>.
			</div>
		</article>

		<h2 class='subtitle'>How can I keep track of my uploads?</h2>
		<article class="message">
			<div class="message-body">
				Simply create a user on the site and every upload will be associated with your account, granting you access to your uploaded files through our dashboard.
			</div>
		</article>

		<h2 class='subtitle'>Why should I use this?</h2>
		<article class="message">
			<div class="message-body">
				There are too many file upload services out there, and a lot of them rely on the foundations of pomf which is ancient. In a desperate and unsuccessful attempt of finding a good file uploader that's easily extendable, chibisafe was born. We give you control over your files, we give you a way to sort your uploads into albums for ease of access and we give you an api to use with ShareX or any other thing that let's you make POST requests. Awesome isn't it? Just like you.
			</div>
		</article>

		<h2 class='subtitle'>I found illegal content hosted here, what should I do?</h2>
		<article class="message">
			<div class="message-body">
				We take illegal content very seriously. If you find any content that is illegal, or that violates your rights, do not hesitate to contact me at the following email address: me[at]r33[dot]space.
			</div>
		</article>
	</div>
</template>

<script>
export default {
	name: 'Faq',
	data() {
		return {};
	},
	head() {
		return {
			title: 'FAQ'
		};
	}
};
</script>

<style lang="scss" scoped>
	@import '~/assets/styles/_colors.scss';
	article.message { background-color: #ffffff; }
</style>
