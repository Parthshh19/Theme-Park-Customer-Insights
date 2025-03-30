# Theme Park Reviews Analysis

### Introduction

This report provides a comprehensive analysis of customer feedback from three major theme park locations: California, Paris, and Hong Kong. The study examines 35,000 verified customer reviews to identify key patterns in visitor demographics, sentiment trends, and operational performance. The analysis was conducted using advanced text mining techniques to extract meaningful insights that can guide business decisions.

The primary objectives of this research were to:

- Understand visitor origin patterns and seasonal trends

- Measure overall customer satisfaction levels

- Identify specific areas requiring operational improvements

- Develop data-driven recommendations for enhancing guest experiences

###  Methodology

2.1 Data Collection and Preparation

The dataset consisted of complete customer reviews collected over a three-year period. Each review contained metadata including a unique identifier, timestamp, reviewer location, and park branch. A rigorous data cleaning process was implemented to ensure analysis quality.

- Text normalization procedures included:

- Removal of HTML tags and special characters

- Conversion to lowercase for consistency

- Stemming to reduce words to their root forms

- Elimination of common stopwords

- Custom filtering of theme park-specific terms

Additional features were engineered to support deeper analysis, including word count metrics and domestic/international visitor classifications. These enhancements allowed for more nuanced examination of review patterns across different visitor segments.

2.2 Analytical Techniques

The study employed multiple analytical approaches to extract insights from the review data:

Sentiment Analysis

The VADER (Valence Aware Dictionary and sEntiment Reasoner) model was selected for its effectiveness in analyzing social media-style text. The model was customized with a domain-specific lexicon to better capture theme park terminology and expressions.

Topic Modeling

Latent Dirichlet Allocation (LDA) was implemented to identify recurring themes within the review corpus. The model was optimized through coherence score analysis and hyperparameter tuning to ensure meaningful topic extraction.

Geospatial and Temporal Analysis

Visitor origin data was geocoded and analyzed to identify geographic trends. Time-series decomposition techniques were applied to understand seasonal visitation patterns.

### Key Findings

3.1 Visitor Demographics 

The analysis revealed distinct visitor patterns across the three park locations:

- California predominantly attracts visitors from the United States, Australia, and Canada.

- Hong Kong has a more diverse visitor base with significant contributions from Australia, India, and the Philippines.

- Paris has a strong visitor base from the United Kingdom and also attracts visitors from the United States and Australia.

Potential Reasons for Differences:

Geographical Proximity:

- California attracts many visitors from the United States due to its location.
- Hong Kong sees a significant number of visitors from neighboring Asian countries reflecting its accessibility and appeal to tourists from nearby regions.
- Paris attracts a large number of visitors from the United Kingdom due to its proximity.

Cultural and Historical Ties:

- Paris, being a major tourist destination in Europe, attracts many visitors from European countries.
- Hong Kong's diverse visitor base might be influenced by its status as an international business hub.

3.2 Visitor Patterns

Domestic Visitors

- Peak Months: June (966 visitors) and July (993 visitors)
- Low Months: February (610 visitors) and November (609 visitors)
  
General Pattern: Domestic visits generally peak during the summer months (June and July) and maintain relatively high numbers through the early fall (October).
International Visitors

- Peak Months: August (597 visitors) and September (593 visitors)
- Low Months: February (309 visitors) and November (364 visitors)

General Pattern: International visits see a distinct rise towards late summer and early fall (August and September), with numbers being lower during the winter and early spring months.
Comparative Analysis and Potential Reasons

Seasonal Variations Reasons:

-Domestic Visitors: The highest numbers in June and July suggesting that domestic visitors are likely to travel more during their school holidays and summer breaks.
-International Visitors: Peak visits in August and September might be influenced by international vacation schedules and favorable travel conditions post the peak domestic travel season.
-Weather Patterns: California's summer and early fall offer the best weather for travel, which is appealing to both domestic and international visitors. However, the preference for late summer by international visitors may reflect a desire to avoid the hottest months of July and early August.
-Holiday Seasons: The lower numbers in February for both groups might be due to the post-holiday travel slump, where both domestic and international tourists are less likely to travel right after the busy holiday season in December.
-Economic Factors: International visitors might plan their trips during off-peak times to take advantage of lower airfare and accommodation prices.

3.2 Customer Sentiment Analysis

Sentiment analysis produced several important insights:

Among the three theme parks, Hong Kong received the most positive sentiments with a compound sentiment score of 0.7083, slightly higher than California's 0.6959 and notably higher than Paris's 0.6437. The sentiment analysis shows that Hong Kong has the highest positive sentiment score (0.1805) and the lowest negative sentiment score (0.0338), indicating more favorable customer feedback overall. In contrast, Paris has the lowest compound and positive sentiment scores and the highest negative sentiment score (0.0468), suggesting comparatively less favorable customer experiences. Thus, Hong Kong emerges as the theme park with the most positive customer sentiments.

The theme park branch that received the most positive sentiment for their “services” is California, with a positive sentiment score of 0.79. This indicates that a higher proportion of reviews expressed positive sentiments towards services in the California branch compared to Hong Kong and Paris.

3.3 LDA Model Analysis

Based on the LDA topic modeling results, the primary concerns and interests of customers when visiting theme parks can be summarized as follows:

- Weekday Visits and Souvenirs (Topic 1): Customers discuss visiting on weekdays, purchasing souvenirs, and engaging in games, suggesting interest in the best times to visit and the availability of themed merchandise and activities.

- Accessibility and Facilities (Topic 2): Discussions about disability access, wheelchair facilities, and specific attractions like towers indicate concerns about park accessibility and the need for accommodating facilities.

- Employee Interactions and Events (Topic 3): Topics include employee interactions, annual events, and specific experiences like splash parties, highlighting the importance of staff behavior and special events in customer satisfaction.

- Memorable Experiences (Topic 4): Words like "true," "childhood," and "custom" point to customers valuing authentic, nostalgic, and personalized experiences.

- Reservations and Character Interactions (Topic 5): Interest in making reservations, meeting characters like Minnie Mouse, and celebrating special occasions is evident, showing the demand for organized visits and character engagements.

- Attractions and Thematic Areas (Topic 6): Discussions about attractions like the Grizzly Manor and themed areas such as the jungle indicate a focus on the park's diverse attractions and immersive environments.

- Amenities and Dining Options (Topic 7): Concerns about amenities like toilets, cafes, and food quality (e.g., burgers) reflect the importance of basic facilities and dining experiences.

U.S. visitors show higher interest in topics such as employee interactions (Topic 3), reserving spots (Topic 5), and specific themes like "Grizzly" and "Manor" (Topic 6). This might reflect a focus on service quality, advance planning, and specific attractions or themes.

In contrast, U.K. visitors emphasize disability access and wheelchair availability (Topic 2), as well as amenities like toilets and village areas (Topic 7). This indicates a concern for accessibility and basic facilities.

Potential reasons for these differences could include cultural priorities, with U.K. visitors possibly placing more emphasis on practical aspects and accessibility, while U.S. visitors might prioritize the overall experience and specific attractions.

### Strategic Recommendations

- Targeted Marketing:
  
California: Focus marketing efforts on the U.S. audience, emphasizing summer promotions.

Hong Kong: Develop campaigns targeting diverse Asian countries, highlighting accessibility and diverse attractions.

Paris: Strengthen ties with U.K. visitors, promoting unique European experiences and convenient travel packages.

- Operational Adjustments:

Peak Season Management: Prepare for increased domestic visitor traffic during summer, and international traffic in late summer and early fall in California. This involves staff scheduling, inventory management, and capacity planning.

Accessibility Enhancements: Invest in improving accessibility features, particularly in Hong Kong and Paris, to address the needs of visitors with disabilities.

Service Training: Enhance employee training programs to improve interactions, as customer satisfaction is closely linked to staff behavior.

- Customer Experience Improvements:

Facility Upgrades: Prioritize maintenance and upgrades of basic amenities like toilets and dining areas to meet customer expectations, particularly in Hong Kong and Paris.

Special Events and Reservations: Promote advance reservations and special event planning to cater to visitors' interest in organized visits and celebrations, especially in California.

By implementing these recommendations, the theme parks can enhance visitor satisfaction, attract more diverse demographics, and optimize operations for peak seasons, ultimately driving higher customer loyalty and business growth.
