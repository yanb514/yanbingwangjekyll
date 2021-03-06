---
title: Research
layout: post
description: ''
image: assets/images/pic07.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<!-- <section id="one">
	<div class="inner">
		<header class="major">
			<h2></h2>
		</header>
		<p></p>
	</div>
</section> -->

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/ACC.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Adaptive cruise control modeling and field experiments</h3>
				</header>
				<p>This project explores methods for model parameter estimation on a car-following model using data collected from Adaptive Cruise Control (ACC) enabled vehicles. The proposed methods are batch method least-squares and an online particle filter. Numerical experiments demonstrate the accuracy and computational performance of the methods relative to a commonly used simulation-based optimization approach. The methods are also assessed on empirical data collected from a 2019 model year ACC vehicle driven in a highway environment. Speed, space gap, and relative velocity data are recorded directly from the factory-installed radar unit via the vehicle’s CAN bus. The least-squares method has the fastest run-time performance, and is up to 3 orders of magnitude faster than other methods. The particle filter is faster than real-time, and therefore is suitable in streaming applications in which the datasets can grow arbitrarily large.</p>
				<ul class="actions">
					<li><a href="https://arxiv.org/abs/1911.06454" class="button">Read more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/pic09.jpg %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Automatic data cleaning via tensor factorization for large urban environmental sensor networks</h3>
				</header>
				<p>The US Environmental Protection Agency identifies that urban heat islands can negatively impact a community’s environment and quality of life. Using low cost urban sensing networks, it is possible to measure the impacts of mitigation strategies in communities at a fine-grained scale, informing context-aware policies and infrastructure design. However, fine-grained city-scale data analysis is complicated by common, tedious data cleaning tasks such as removing outliers and imputing missing data. To address the challenge of data cleaning, this article introduces a robust low-rank tensor factorization method to automatically correct anomalies and impute missing entries for high-dimensional urban environmental datasets. We validate the method on a synthetically degraded National Oceanic and Atmospheric Administration temperature dataset, with a recovery error of 4%, and apply it to the Array of Things city-scale sensor network in Chicago, IL.</p>
				<ul class="actions">
					<li><a href="https://www.climatechange.ai/papers/neurips2019/27" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/pic10.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Estimating adaptive cruise control model parameters from on-board radar units</h3>
				</header>
				<p>This project explores methods for model parameter estimation on a car-following model using data collected from Adaptive Cruise Control (ACC) enabled vehicles. The proposed methods are batch method least-squares and an online particle filter. Numerical experiments demonstrate the accuracy and computational performance of the methods relative to a commonly used simulation-based optimization approach. The methods are also assessed on empirical data collected from a 2019 model year ACC vehicle driven in a highway environment. Speed, space gap, and relative velocity data are recorded directly from the factory-installed radar unit via the vehicle’s CAN bus. The least-squares method has the fastest run-time performance, and is up to 3 orders of magnitude faster than other methods. The particle filter is faster than real-time, and therefore is suitable in streaming applications in which the datasets can grow arbitrarily large.</p>
				<ul class="actions">
					<li><a href="https://dl.acm.org/doi/abs/10.1145/3302509.3313325" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>



</div>
