# Analytical Process

## 1. Business Question

The analysis began with a simple BI question: was Olist’s marketplace growth broadly distributed, or was performance meaningfully dependent on a narrower set of revenue drivers? This mattered because topline growth alone could not show whether marketplace expansion was being supported by broad participation or shaped disproportionately by leading sellers and categories.

## 2. Analytical Framing

To answer that question, the analysis focused on three main lenses:

- seller concentration
- category contribution
- revenue and order activity over time

These three lenses were chosen because they allowed marketplace performance to be judged from both a structural and activity-based perspective. Seller and category views help reveal concentration, while time-based revenue and order trends help show whether growth is supported by broader marketplace activity.

## 3. Data Scope and Modeling Decisions

The project used the public Olist Brazilian ecommerce dataset and narrowed the working model to the entities most relevant for marketplace revenue analysis:

- orders
- order items
- products
- sellers
- customers

The model was structured to support seller-level, category-level, and time-based reporting. Portuguese product category labels were translated into English for readability, and a dedicated Date table was created to support time intelligence and consistent monthly analysis.

## 4. Measure Logic

The measure layer was built to support both topline monitoring and concentration analysis. Core measures included:

- Total Revenue
- Total Orders
- Average Order Value
- Active Sellers
- Revenue per Seller
- Top 10 Sellers’ Revenue Share %
- Top Category Contribution %

These measures were chosen because they helped separate raw scale from structural dependence. Revenue and order metrics showed overall marketplace size and activity, while share-based measures made it possible to judge whether performance was broadly distributed or concentrated.

## 5. Dashboard Structure Logic

The report was organized into two pages.

**Executive Overview** was designed to surface marketplace scale, trend, and concentration signals in one place.  
**Marketplace Driver Analysis** was designed to support deeper inspection of seller- and category-level contribution through ranking and comparison views.

This two-page structure helped the analysis move from summary to explanation rather than forcing all interpretation into a single page.

## 6. Interpretation Logic

The interpretation focused on whether concentration was visible, whether it was extreme, and whether broader marketplace participation was still present.

The results showed that:

- the top 10 sellers contributed 13.15% of total revenue
- the top category contributed 9.26% of total revenue
- revenue and order trends rose together over time

Taken together, these signals suggested that Olist’s growth was not evenly distributed, but neither was it dominated by a single narrow source. The marketplace appeared broad enough to show meaningful participation, while still shaped by visible concentration in leading sellers and categories.

## 7. Limits of the Analysis

This project was designed to assess marketplace dependence through revenue structure, not to provide a full commercial diagnosis.

The analysis does not include:
- profit or margin data
- customer retention or cohort analysis
- acquisition cost or marketing channel efficiency
- causal inference about why concentration exists

Because of that, the dashboard supports a structured view of marketplace dependence, but not a complete explanation of underlying business causes.
