# Rating Amazon Product and Sorting Reviews

## Business Problem

One of the pivotal challenges in the realm of e-commerce pertains to the accurate computation of post-purchase ratings
for products. Addressing this issue not only fosters heightened customer satisfaction for the e-commerce platform but
also serves to accentuate product visibility for sellers, thereby ensuring a seamless shopping experience for
purchasers. Another noteworthy concern involves the appropriate sorting of product reviews. Given that misleading
reviews can exert a direct impact on product sales, the repercussions encompass both financial losses and customer
attrition. Effectively resolving these two foundational issues holds the promise of augmenting sales for e-commerce
entities and sellers, while concurrently facilitating a frictionless completion of the purchasing journey for customers.

## Dataset Story

This dataset comprises Amazon product information, including diverse metadata and product categories. Specifically, it
features user ratings and reviews for the product within the electronics category that has garnered the highest number
of reviews.

## Features

- `reviewerID` - Unique identifier for the reviewer
- `asin` - Unique identifier for the product
- `reviewerName` - Username of the reviewer
- `helpful` - Degree of helpfulness of the review
- `reviewText` - Detailed review text
- `overall` - Overall rating given to the product
- `summary` - Brief summary of the review
- `unixReviewTime` - Timestamp of the review in Unix format
- `reviewTime` - Human-readable timestamp of the review
- `day_diff` - Number of days elapsed since the review
- `helpful_yes` - Number of users finding the review helpful
- `total_vote` - Total number of votes received by the review