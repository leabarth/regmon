<h1 class="about-title">Über REGmon</h1>
<div class="about-container">
	<div class="about-section about-logo-center">
		<img
			src="/src/lib/assets/regmon-logo-sm.png"
			alt="REGmon Logo klein"
			class="about-logo-small"
		/>
		<h2>REGmon</h2>
		<p class="about-subtitle">Athletenmonitoring<br />in Sportpraxis und Wissenschaft</p>
	</div>
	<div class="about-section">
		<p>
			REGmon ist ein <strong>Open Source-Projekt</strong> und durch eine <strong>MIT-Lizenz</strong>
			lizensiert.
		</p>
		<p><a href="https://regmon-project.org/" target="_blank">regmon-project.org</a></p>
		<p>
			REGmon wurde im Rahmen des Projekts <em
				>"Optimierung von Training und Wettkampf: Regenerationsmanagement im Spitzensport" (REGman)</em
			> entwickelt, das im Rahmen des WVL-Forschungsprogramms vom Bundesinstitut für Sportwissenschaft
			von 2012 bis 2021 gefördert wurde.
		</p>
		<p>
			REGman-Projektdokumentation im Open Science Framework (OSF):<br />
			<a href="https://osf.io/uz4af/" target="_blank">osf.io/uz4af/</a>
		</p>
		<p>Das Projekt wurde von der <strong>CEOS Solution GmbH (Bochum)</strong> unterstützt.</p>
		<p class="about-support">
			Wenn Sie für die vorliegende Software-Instanz Hilfe benötigen, kontaktieren Sie bitte:<br />
			<a href="mailto:support@domain.com">support@domain.com</a>
		</p>
		<p class="about-version"><strong>Version: 1.0.27</strong></p>
	</div>
</div>

<style>
	.about-title {
		text-align: center;
		margin-top: 2rem;
		color: var(--theme-primary, #2a4d69);
	}
	.about-container {
		max-width: 700px;
		margin: 2rem auto;
		background: var(--theme-bg, #fff);
		border-radius: 1rem;
		box-shadow: 0 2px 12px rgba(0, 0, 0, 0.07);
		padding: 2rem 2.5rem;
		display: flex;
		flex-direction: column;
		gap: 2rem;
	}
	.about-section {
		text-align: center;
	}
	.about-logo-center {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	.about-logo {
		width: 120px;
		margin-bottom: 1rem;
		display: block;
		margin-left: auto;
		margin-right: auto;
	}
	.about-logo-small {
		width: 48px;
		margin-bottom: 0.5rem;
		margin-left: 0.5rem;
		vertical-align: middle;
		display: block;
		margin-left: auto;
		margin-right: auto;
	}
	.about-subtitle {
		font-size: 1.1rem;
		color: var(--theme-secondary, #4b86b4);
		margin-bottom: 1.5rem;
	}
	.about-support {
		margin-top: 2rem;
		font-size: 1rem;
	}
	.about-version {
		margin-top: 1.5rem;
		font-size: 1.1rem;
		color: var(--theme-primary, #2a4d69);
	}
	@media (max-width: 600px) {
		.about-container {
			padding: 1rem;
		}
		.about-logo {
			width: 80px;
		}
	}
</style>
