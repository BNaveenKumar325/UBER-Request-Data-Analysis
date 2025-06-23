This project involves performing a comprehensive Exploratory Data Analysis (EDA) on the Uber Request Dataset with the goal of understanding customer demand patterns, operational inefficiencies, and driver availability issues. The dataset contains information about ride requests including timestamps, pickup points (City or Airport), request status (Trip Completed, Cancelled, No Cars Available), and driver assignments. The analysis was carried out using Python and a wide range of visualization techniques structured under the UBM (Univariate, Bivariate, Multivariate) methodology.

Univariate Analysis

Univariate visualizations were used to explore the individual distribution of categorical and numerical variables. It was found that a significant proportion of ride requests did not result in trip completion — either due to cancellations or unavailability of cars. The majority of requests originated from the City, indicating it is a high-demand location. Hour-wise analysis revealed peak demand times in two clear windows: morning (5–10 AM) and evening (5–9 PM). A histogram of trip durations indicated that most successful rides lasted less than 60 minutes, with a heavy right-skew showing a few longer trips.

Bivariate Analysis

In the bivariate stage, we analyzed relationships between two variables such as request hour vs. status, pickup point vs. status, and pickup point vs. trip duration. One key insight was that cancellations were disproportionately high in the City during morning hours, while the Airport suffered mostly from unavailability of cars during the evening peak. Box plots showed that trip durations from the Airport tend to be longer than those from the City. Status-wise breakdowns by hour revealed operational pressure during peak times, where demand far exceeds driver supply.

Multivariate Analysis

The multivariate analysis brought in a combination of time, location, and status to provide deeper context. A heatmap of cancellations by pickup point and hour visually reinforced demand–supply mismatches. Violin plots and swarm plots further showed variations in trip durations across statuses and pickup points. Faceted bar charts made it clear that time and location jointly influence operational performance. A correlation matrix confirmed that while time-based features had some influence, the dominant issues were categorical in nature—namely, pickup point and trip status.
