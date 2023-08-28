<nav>
	<div class="leftSide">
		<img src="./Logo.png" alt="Logo" />
		<div class="Logo-text">
			<p>Losangles</p>
			<p>Mountains</p>
		</div>
	</div>
	<ol>
		<li>History</li>
		<li>Team</li>
	</ol>
</nav>

<style>
	nav {
		position: absolute;
		top: 0;
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		width: 70vw;
		height: 100px;
	}
	.leftSide {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 80%;
	}
	.leftSide .Logo-text {
		height: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		font-weight: 900;
		text-transform: uppercase;
		margin-left: 1rem;
	}
	.leftSide .Logo-text p:nth-of-type(1) {
		color: #4d4d4d;
	}
	.leftSide .Logo-text p:nth-of-type(2) {
		color: #5f749f;
	}
	.leftSide img {
		width: 40px;
		height: 40px;
	}
	ol {
		list-style: decimal-leading-zero;
		font-family: var(--ff-General-Sans);
		font-style: italic;
		display: flex;
		justify-content: space-between;
		width: 10vw;
		align-items: center;
	}
	ol li {
		border-bottom: 1px solid #fff;
		text-transform: uppercase;
		color: #fff;
		margin-left: 2rem;
	}
</style>
