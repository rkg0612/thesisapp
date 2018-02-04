<template>
	<f7-page>
		<f7-navbar title="Form" back-link="Back" sliding></f7-navbar>
		<f7-block-title>Form</f7-block-title>
		<f7-list form>
			<f7-list-item>
				<f7-label>Name</f7-label>
				<f7-input type="text" placeholder="Name"></f7-input>
			</f7-list-item>
			<f7-list-item>
				<f7-label>E-mail</f7-label>
				<f7-input type="email" placeholder="E-mail"></f7-input>
			</f7-list-item>
			<f7-list-item>
				<f7-label>Phone</f7-label>
				<f7-input type="tel" placeholder="Phone"></f7-input>
			</f7-list-item>
			<f7-list-item>
				<f7-label>Comments:</f7-label>
			</f7-list-item>
			<f7-list-item>
				<f7-input type="textarea" placeholder="Type Here..."></f7-input>
			</f7-list-item>
		</f7-list>
		<f7-block inner>
			<p>
				<f7-grid>
					<f7-col><f7-button big fill color="green">Submit</f7-button></f7-col>
				</f7-grid>
			</p>
		</f7-block>
	</f7-page>
</template>

<script>
	export default {}
</script>