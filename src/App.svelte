<script lang="ts">
	import bananaLogo from "./assets/banana-logo.svg?raw";
	import TextTrain from "./lib/TextTrain.svelte";
</script>

<main class="app">
	<nav>
		<a href="/" class="logo">
			{@html bananaLogo}
		</a>
		<p class="description">
			“banana economy” describes today’s market gone completely bananas,
			driven by irrational AI hype, inflated valuations, and circular
			investments.
		</p>
	</nav>
	<TextTrain text="THEMARKETCANSTAYIRRATIONALLONGERTHANYOUCANSTAYSOLVENT" />

	<ul class="news">
		<li>
			<a
				href="https://www.bloomberg.com/opinion/articles/2025-11-11/ai-bubble-is-ignoring-big-short-michael-burry-chip-depreciation-fears"
			>
				The AI Bubble Is Ignoring Michael Burry’s Fears
			</a>
			Chris Bryant, Bloomberg, Nov. 11, 2025
		</li>
		<li>
			<a
				href="https://fortune.com/2025/11/11/softbank-nvidia-openai-masayoshi-son-sam-altman-investment/"
			>
				Softbank goes all-in on OpenAI to the tune of $30 billion
			</a>
			Dave Smith, Fortune, Nov. 11, 2025
		</li>
		<li>
			<a
				href="https://www.bloomberg.com/news/articles/2025-11-11/microsoft-plans-to-invest-10-billion-in-portugal-ai-data-hub"
			>
				Microsoft to Invest $10 Billion in AI Data Hub in Portugal
			</a>
			Bloomberg, Nov. 11, 2025
		</li>
		<li>
			<a
				href="https://www.bloomberg.com/news/articles/2025-11-10/ai-s-5-trillion-data-center-boom-will-dip-into-every-debt-market-jpmorgan-says"
			>
				AI’s $5 Trillion Cost Needs Every Debt Market, JPMorgan Says
			</a>
			Victor Swezey, Bloomberg, Nov. 10, 2025
		</li>
		<li>
			<a
				href="https://techcrunch.com/2025/11/05/softbank-openai-launch-new-joint-venture-in-japan-as-ai-deals-grow-ever-more-circular/"
			>
				SoftBank, OpenAI launch new joint venture in Japan as AI deals
				grow ever more circular
			</a>
			Ram Iyer, TechCrunch, Nov. 5, 2025
		</li>
		<li>
			<a
				href="https://www.theverge.com/ai-artificial-intelligence/812455/ai-industry-earnings-bubble-fomo-hype"
			>
				The AI industry is running on FOMO
			</a>
			Hayden Field, The Verge, Nov. 3, 2025
		</li>
		<li>
			<a
				href="https://www.cnbc.com/2025/11/03/open-ai-amazon-aws-cloud-deal.html"
			>
				Amazon closes at record after $38 billion OpenAI deal with AWS
			</a>
			MacKenzie Sigalos, CNBC, Nov. 3, 2025
		</li>
		<li>
			<a
				href="https://techcrunch.com/2025/11/02/sam-altman-says-enough-to-questions-about-openais-revenue"
			>
				Sam Altman says ‘enough’ to questions about OpenAI’s revenue
			</a>
			Anthony Ha, TechCrunch, Nov. 2, 2025
		</li>
		<li>
			<a
				href="https://www.nytimes.com/2025/10/29/technology/nvidia-value-market-ai.html"
			>
				Nvidia Is Now Worth $5 Trillion as It Consolidates Power in A.I.
				Boom
			</a>
			Tripp Mickle, The New York Times, Oct. 29, 2025
		</li>
		<li>
			<a
				href="https://www.cnbc.com/2025/10/29/amazon-opens-11-billion-ai-data-center-project-rainier-in-indiana.html"
			>
				Amazon opens $11 billion AI data center in rural Indiana
			</a>
			MacKenzie Sigalos, CNBC, Oct. 29, 2025
		</li>
		<li>
			<a
				href="https://www.bloomberg.com/news/articles/2025-10-02/openai-completes-share-sale-at-record-500-billion-valuation"
			>
				OpenAl Valuation Reaches $500 Billion, Topping Musk's SpaceX
			</a>
			Shirin Ghaffary, Bloomberg, Oct. 2, 2025
		</li>
		<li>
			<a
				href="https://www.cnbc.com/2025/09/02/anthropic-raises-13-billion-at-18-billion-valuation.html"
			>
				Anthropic raises $13 billion funding round at $183 billion
				valuation
			</a>
			Ashley Capoot, CNBC, Sep. 2, 2025
		</li>
		<li>
			<a
				href="https://www.nytimes.com/2025/08/13/business/ai-business-payoff-lags.html"
			>
				Companies Are Pouring Billions Into A.I. It Has Yet to Pay Off.
			</a>
			Steve Lohr, The New York Times, Aug. 13, 2025
		</li>
		<li>
			<a
				href="https://www.wired.com/story/thinking-machines-lab-mira-murati-funding/"
			>
				Thinking Machines Lab Raises a Record $2 Billion, Announces
				Cofounders
			</a>
			Will Knight, Wired, Jul. 15, 2025
		</li>
		<li>
			<a
				href="https://www.cnbc.com/2025/06/10/zuckerberg-makes-metas-biggest-bet-on-ai-14-billion-scale-ai-deal.html"
			>
				Meta nears $14 billion stake in Scale AI, hires founder Wang
			</a>
			Jonathan Vanian and Ashley Capoot, CNBC, Jun. 11, 2025
		</li>
		<li>
			<a
				href="https://www.nytimes.com/2025/05/21/technology/openai-jony-ive-deal.html"
			>
				OpenAI Unites With Jony Ive in $6.5 Billion Deal to Create A.I.
				Devices
			</a>
			Mike Isaac & Cade Metz, The New York Times, May 21, 2025
		</li>
		<li>
			<a
				href="https://www.cnbc.com/2025/03/31/openai-closes-40-billion-in-funding-the-largest-private-fundraise-in-history-softbank-chatgpt.html"
			>
				OpenAI closes $40 billion funding round, largest private tech
				deal on record
			</a>
			Hayden Field and Kate Rooney, CNBC, Mar. 1, 2025
		</li>
		<li>
			<a
				href="https://www.bloomberg.com/news/articles/2025-01-24/zuckerberg-warns-of-higher-than-expected-capex-at-meta-in-2025"
			>
				Meta to Spend Up to $65 Billion on Al in '25
			</a>
			Dana Wollman and Kurt Wagner, Bloomberg, Jan. 24, 2025
		</li>
		<li>
			<a
				href="https://www.cnbc.com/2025/02/06/amazon-expects-to-spend-100-billion-on-capital-expenditures-in-2025.html"
			>
				Amazon plans to spend $100 billion this year to capture ‘once in
				a lifetime opportunity’ in AI
			</a>
			Annie Palmer, CNBC, Feb. 6, 2025
		</li>
		<li>
			<a
				href="https://www.cnn.com/2025/01/21/tech/openai-oracle-softbank-trump-ai-investment"
			>
				Stargate: Trump announces a $500 billion AI infrastructure
				investment in the US
			</a>
			Clare Duffy, CNN Business, Jan. 21, 2025
		</li>
		<li>
			<a
				href="https://finance.yahoo.com/news/elon-musks-xai-raises-6-105243107.html"
			>
				Elon Musk's xAI raises $6 billion in its Series C fundraising
			</a>
			Theron Mohamed, Yahoo Finance, Dec. 24, 2024
		</li>
		<li>
			<a
				href="https://www.404media.co/ai-friend-company-spent-1-8-million-and-most-its-funds-on-domain-name/"
			>
				AI 'Friend' Company Spent $1.8 Million and Most of Its Funds on
				Domain Name
			</a>
			Emanuel Maiberg and Jason Koebler, 404 Media, Jul. 30, 2024
		</li>

		<a class="me" href="https://abe.computer"> by abe </a>
	</ul>
</main>

<style lang="scss">
	.app {
		--padding: 1rem;
		position: relative;
		width: 100vw;
		min-height: 100vh;
		overflow: hidden;

		display: flex;
		flex-direction: column;
		padding: var(--padding);
		box-sizing: border-box;
	}
	nav {
		display: flex;
		flex-direction: column;
		padding-bottom: 0;
	}
	.logo {
		display: inline-block;
		width: 100px;
		:global(svg) {
			width: 100%;
			height: auto;
		}
	}
	ul {
		display: flex;
		flex-direction: column;
		margin-top: 140px;
		padding: 0;
		max-width: 80vw;
		flex: 1;
		list-style: none;
		gap: 0.5rem;
		li a {
			color: #c88f1a;
			text-decoration: underline;
		}
		li:last-of-type {
			margin-bottom: 4rem;
		}
		.me {
			margin-top: auto;
		}
	}
	@media (min-width: 800px) {
		.app {
			--padding: 2rem;
		}
		nav {
			flex-direction: row;
			justify-content: space-between;
			.description {
				max-width: 400px;
			}
		}
		.logo {
			width: 140px;
		}
	}
</style>