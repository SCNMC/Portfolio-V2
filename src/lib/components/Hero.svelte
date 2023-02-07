<section>
	<p>Portfolio</p>
	<p>2023</p>
	<p>Student</p>
	<p>Frontend</p>
	<p>Design&</p>
	<p>Development</p>
	<p>Github</p>
	<p>Instagram</p>
</section>

<style>
	section {
		display: grid;
		align-items: center;
		justify-items: center;
		grid-template-columns: 1fr 1.2fr 1fr;
		grid-template-rows: repeat(4, 1fr);
		grid-column-gap: 0px;
		grid-row-gap: 0px;
		min-height: 85vh;
	}
	p {
		font-size: 3.5em;
	}
	section :first-of-type {
		border-top: 4px solid #000;
		border-bottom: 4px solid #000;
		width: 100%;
		padding: 0.2em;
	}

	section :nth-child(1) {
		grid-area: 3 / 3 / 1 / 2;
		margin: 0 auto;
	}
	section :nth-child(2) {
		grid-area: 3 / 2 / 1/ 4;
	}
	section :nth-child(3) {
		grid-area: 2 / 3 / 3 / 2;
		border-bottom: 4px solid #000;
		width: 100%;
		padding: 0.2em;
		margin: 0 auto;
	}
	section :nth-child(4) {
		grid-area: 2 / 2 / 3 / 5;
		transform: translateX(-22%);
	}
	section :nth-child(5) {
		grid-area: 2 / 3 / 4 / 2;

		border-bottom: 4px solid #000;
		width: 100%;
		padding: 0.2em;
		margin: 0 auto;
	}
	section :nth-child(6) {
		grid-area: 2 / 2 / 4 / 5;
		transform: translateX(-30%);
	}
	section :nth-child(7) {
		grid-area: 3 / 3 / 4 / 2;

		border-bottom: 4px solid #000;
		width: 100%;
		padding: 0.2em;
		margin: 0 auto;
	}
	section :nth-child(8) {
		grid-area: 3 / 2 / 4 / 5;
		transform: translateX(-22%);
	}
</style>
