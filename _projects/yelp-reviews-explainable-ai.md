---
title: "Snack and Snap: A Novel Recipe for Yelp Reviews with Explainable AI"
authors: "Yonah Byarugaba, Binyang Wang, Rajiv Garg"
venue: "Proceedings of the 58th Hawaii International Conference on System Sciences (HICSS)"
year: 2025
status: published
theme: "Consumer Behavior & Text Analytics"
order: 1
link: "https://hdl.handle.net/10125/109312"
---
Platforms like Yelp, Google Maps, Instagram, and Amazon lean heavily on user-submitted images, yet most still require separate text and star ratings to capture intent — even though a photo often already encodes it. This project extracts interpretable visual features (edge distribution, color distribution, embedded text, focus, brightness, contrast) from review images and tests how well simple, explainable models can predict the rating a user attached to that image.

The result: features as simple as brightness and contrast meaningfully explain image-level ratings, and models like random forest and logistic regression reach a 0.84 F-1 score — competitive with far less interpretable approaches. The implication is practical: platforms could auto-generate user intent and ratings directly from shared images, simplifying how information moves through review ecosystems.

### Abstract
Pictures are worth a thousand words, yet most platforms require users to also provide text, ratings, and images. Images often capture a user's intent, and features within images typically correlate with that intent. This paper extracts features from images (edge distribution, color distribution, embedded text, focus, and more) and compares simple vs. complex models for predicting the ratings associated with them. Brightness and contrast are found to significantly explain image-level ratings, with random forest and logistic regression models achieving a 0.84 F-1 score. In the era of generative AI, the authors anticipate that sharing an image alone could let platforms auto-generate user intent and ratings, simplifying the dissemination of information.
