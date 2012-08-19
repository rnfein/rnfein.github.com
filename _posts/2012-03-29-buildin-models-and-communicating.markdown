---
layout: page
type: text
title: 'Is your team building run-time models? Make sure you’re communicating with the business.'
date: 2012-03-29
---

After spending time building and maintaining the run-time models central to our business at [www.intentmedia.com](http://www.intentmedia.com), here are a few observations about communicating to bridge the gap between data and engineering teams, and the rest of the business:

## Availability of Data

The business needs to know what data your models rely on.  With the help of the business, validate that you’re avoiding privacy issues and that the data is generally kosher.  If you don’t directly control all of your model input data, make sure the folks talking to your partners about data availability understand what data is important and what battles are worth fighting.  A business team that actively works to prevent “data deprecation” and encourage “data exposure” is a tremendous asset to any data team.  Refresh, disseminate and validate data dependencies each time your production models change.

If, on the other hand, your models rely on providers’ feeds, you’re generally in decent shape from an availability perspective: the structure and quality of the supplied data should remain relatively constant.  In these cases, one of the biggest risks to data availability is getting and maintaining access to the data at a reasonable price.  The better the business understands and is able articulate the value of a certain piece of data to your models, the more likely it is to take care of the feed’s commercials.  Articulate why it is important that the data you rely on be made available and remain available.

## Available Data Changes, Especially when Modeling Internet Traffic at Large

Traffic and software constantly change.  As a result, available data can vary drastically over time.  For example, a browser vendor may introduce a privacy setting that blocks cookies by default, a traffic source may change the way a referrer header is set, or seasonality may alter the traffic composition and behavior.  Set the expectation that your models require continuous investment and monitoring in order to maintain and understand quality, even if you’ve built an adaptive system.  Make an attempt to convince your business to appreciate this fact and understand the resource implications.

## Setting Performance Expectations

Often, one of your behavioral models likely controls a decision that influences a key operational performance indicator of your business.  (For example, at an ad-serving company, predicting a click through rate could greatly affect top-line revenue.)  Given that available data and traffic changes constantly, set the expectation with the business that small fluctuations and variance from target KPIs as a result of model behavior are perfectly normal: depending on the application, it may be difficult (and costly) to manage a predictive model to an arbitrary precision on a daily basis.   Like all monitoring, having visibility into performance (of either KPIs or models) provides value until it constantly sends a team into panic as it seeks to understand a KPI change that results from normal operating circumstances.

If refreshing or changing the model definitions can introduce a second order effect on the performance of the business, work to understand that effect and communicate it when you refresh or change your model: not all business stakeholders will have a comparable intuition to your data or engineering teams about how your model can affect the bigger picture.

## Prototyping and Ideas

Often, one of your partners or peers likely has experience in an analogous problem that may help you solve your own problem.  Don’t be shy: encourage the business to talk to the market about what data they might examine to get your modeling to the next level.  Make the business and your market your partners in brainstorming how you can incorporate more data.

Set the expectation that most modeling experimentation results in failure.  Convince the business that providing adequate resources to minimize the cost and cycle time of experimentation is a good strategy.  Foster a sense of progress by celebrating and communicating quick cycles resulting in either success or failure.

## Time and the Value of Data

If your business is like ours, there is a significant time component to the value of data.  If we hypothesize that a certain piece of data will be valuable, we need to make an effort to collect it now so we have enough data to make it useful in the future.  Working with the business to prioritize resources for data collection when its value hasn’t been proven is difficult: the catch is that you can’t prove it is valuable until you’ve collected and prototyped with it!  Set the expectation with the business that spending resources to collect data is valuable and resource-worthy: knowing that a certain piece of data is not valuable is often just as useful as knowing what data is valuable.

## The Math and Context

Explaining the math and the approaches behind the modeling to the business is more often only an efficient use of time if it aids in appreciating the context of a problem or an outcome the business must resolve.  For example, if there are constraints as to how well a model performs given certain input data and it is important for the business to understand or appreciate that fact, it may be worth providing context with a layman’s math explanation.  In most cases, communicating math or detailed mechanics to the business won’t be a productive use of anyone’s time.  Instead, regularly communicate context to the business through visualization in your dashboards – business folk love dashboards.
