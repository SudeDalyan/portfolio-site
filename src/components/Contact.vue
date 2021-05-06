<template>
<div class="row">
<div class="col-lg-6">
<img src="../assets/reading.gif">
</div>
<div class="col-lg-6">
<form>
		<h1 class="title text-center mb-4">Contact Me</h1>

			<!-- Name -->
			<div class="form-group position-relative">
				<input type="text" id="formName" class="form-control form-control-lg thick" placeholder="Name">
			</div>

			<!-- E-mail -->
			<div class="form-group position-relative">
				<input type="email" id="formEmail" class="form-control form-control-lg thick" placeholder="E-mail">
			</div>

			<!-- Message -->
			<div class="form-group message">
				<textarea id="formMessage" class="form-control form-control-lg" rows="7" placeholder="Message"></textarea>
			</div>
		
			<!-- Submit btn -->
			<div class="text-center">
				<button type="submit" class="btn btn-primary" tabIndex="-1">Send Message</button>
			</div>
	</form>

</div>
</div>
</template>