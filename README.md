# 📊 Amazon Products EDA Dashboard

## 🎯 Project Overview

A comprehensive Exploratory Data Analysis (EDA) project that analyzes Amazon product reviews dataset to uncover valuable business insights about product ratings, pricing strategies, category performance, and market trends.

## 🚀 Features

### 📈 Interactive Dashboards
- **Executive Summary Dashboard** - Key metrics and KPIs at a glance
- **Category Analysis Dashboard** - Performance metrics across product categories
- **Price Analysis Dashboard** - Pricing trends and distribution analysis
- **Rating & Review Analysis Dashboard** - Customer satisfaction insights
- **Advanced Analytics Dashboard** - Correlation analysis and top performers
- **Market Trends Dashboard** - Opportunity mapping and trend analysis

### 🔍 Key Insights Delivered
- Product performance analysis across 1,465 records
- Price-quality relationship analysis
- Category-wise performance comparison
- Discount strategy effectiveness
- Customer rating patterns and trends
- Market opportunity identification
- Business recommendations based on data

## 🛠️ Technology Stack

- **Python 3.8+** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Plotly** - Interactive visualizations
- **Matplotlib & Seaborn** - Statistical plotting
- **Scikit-learn** - Machine learning utilities
- **Jupyter Notebook** - Development environment

## 📁 Project Structure

```
amazon-eda-project/
│
├── amazon.csv                          # Dataset file
├── amazon_eda_comprehensive.ipynb      # Main analysis notebook
├── README.md                           # Project documentation
└── myenv/                              # Virtual environment
    └── [Python dependencies]
```

## ⚡ Quick Start

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd amazon-eda-project
   ```

2. **Set up virtual environment**
   ```bash
   python -m venv myenv
   
   # Windows
   myenv\Scripts\activate
   
   # macOS/Linux
   source myenv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn scipy missingno jupyter
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook amazon_eda_comprehensive.ipynb
   ```

## 📊 Dataset Information

- **Records**: 1,465 Amazon products
- **Features**: 16 columns including ratings, prices, categories, reviews
- **Coverage**: Multiple product categories with comprehensive review data
- **Data Quality**: Cleaned and preprocessed for analysis

### Key Columns:
- `product_id` - Unique product identifier
- `product_name` - Product title
- `category` - Product category hierarchy
- `discounted_price` - Current selling price
- `actual_price` - Original price
- `discount_percentage` - Discount offered
- `rating` - Customer rating (1-5 scale)
- `rating_count` - Number of reviews
- `about_product` - Product description
- `user_id` - Customer identifier
- `user_name` - Customer name
- `review_id` - Review identifier
- `review_title` - Review headline
- `review_content` - Review text
- `img_link` - Product image URL
- `product_link` - Product page URL

## 🎨 Visualization Highlights

### Executive Summary
- **Total Products Analyzed**: 1,460 unique products
- **Average Customer Rating**: 4.10/5.0
- **Average Discount**: 40.1%
- **Total Reviews**: 26.7M+ customer reviews

### Key Findings
- 📈 **75.8%** of products have ratings ≥ 4.0/5.0
- 💰 **Most products** priced under ₹1,000
- 🏆 **Electronics** category dominates the marketplace
- 🎯 **30-60% discount range** shows optimal customer satisfaction

## 🔬 Analysis Sections

### 1. Data Cleaning & Preprocessing
- Missing value analysis
- Price data normalization
- Rating data standardization
- Feature engineering for analysis

### 2. Exploratory Data Analysis
- Distribution analysis of key metrics
- Category performance comparison
- Price-rating relationship exploration
- Discount effectiveness evaluation

### 3. Advanced Analytics
- Correlation matrix analysis
- Performance scoring algorithms
- Market opportunity mapping
- Value-for-money product identification

### 4. Business Intelligence
- Strategic recommendations
- Market positioning insights
- Pricing strategy guidance
- Category expansion opportunities

## 📈 Business Impact

### Strategic Insights
- **Category Focus**: Electronics & Computer Accessories show strong performance
- **Pricing Strategy**: Optimal discount range of 30-60% for maximum satisfaction
- **Quality Focus**: Maintaining 4+ ratings crucial for competitive advantage
- **Market Positioning**: Value-conscious customer targeting recommended

### Actionable Recommendations
1. **Expand** in high-performing, underserved categories
2. **Optimize** pricing in the 30-60% discount sweet spot
3. **Focus** on building strong review bases for credibility
4. **Target** sub-₹1000 price points for maximum market reach

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Vishnu P Rajagopal**
- 📧 Email: vishnurajagopal28@gmail.com
- 💼 LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/vishnu-p-rajagopal-585b8b216/)
- 🐙 GitHub: [@yourusername](https://github.com/Vishnudrm)

## 🙏 Acknowledgments

- Amazon for providing the rich dataset
- Python community for excellent data science libraries
- Plotly team for interactive visualization capabilities
- Jupyter Project for the excellent notebook environment

## 📞 Support

If you have any questions or need assistance:
1. 📖 Check the documentation in the notebook
2. 🐛 Open an issue for bugs
3. 💡 Submit feature requests via issues
4. 📧 Contact the author directly

---

⭐ **Star this repository if you found it helpful!** ⭐

## 🏷️ Tags

`data-analysis` `python` `pandas` `plotly` `jupyter-notebook` `eda` `amazon` `business-intelligence` `data-visualization` `market-analysis`
