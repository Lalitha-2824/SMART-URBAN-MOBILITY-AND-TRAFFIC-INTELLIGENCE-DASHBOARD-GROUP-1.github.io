# 🚦 Urban Pulse
### Smart Urban Mobility & Traffic Intelligence Dashboard

<p align="center">
  <b>Turning Urban Mobility Data into Actionable Insights</b>
</p>

<p align="center">
  📍 Bengaluru, India &nbsp; | &nbsp;
  📊 Power BI &nbsp; | &nbsp;
  🗄️ Data Warehouse &nbsp; | &nbsp;
  🔄 ETL &nbsp; | &nbsp;
  📈 Data Analytics
</p>

---

## 🌆 What is Urban Pulse?

**Urban Pulse** is a data-driven **Smart City Mobility Analytics Platform** designed to bring different urban mobility datasets together and convert them into meaningful insights.

Instead of looking at transit, traffic, weather, and mobility data separately, Urban Pulse creates a **unified analytical environment** where these datasets can be explored through interactive dashboards.

### 💡 In simple words:

> **Collect → Clean → Integrate → Analyze → Visualize → Understand Urban Mobility**

---

# 🎯 Why Urban Pulse?

Cities generate huge amounts of transportation data every day.

But this data often comes from different sources and has different:

- 📋 Data formats
- ⏱️ Timestamp formats
- 📍 Location identifiers
- 🚌 Transit structures
- 🚦 Traffic information

Urban Pulse brings these datasets together to answer questions like:

> 🚌 Which routes have higher transit activity?

> 🚦 Which areas experience more traffic problems?

> 🌦️ How do environmental conditions relate to mobility?

> 📍 Which areas may have mobility accessibility gaps?

> 📊 What are the major mobility trends?

---

# 🏗️ Project Architecture

```text
                    🌐 DATA SOURCES
                         │
        ┌────────────────┼────────────────┐
        │                │                │
      🚌 Transit       🚦 Traffic       🌦️ Weather
        │                │                │
      🚇 Metro        Incidents       Climate Data
        │                │                │
      🚆 Railway       Areas          Time Data
        │                │                │
        └────────────────┼────────────────┘
                         ↓
                 🔄 DATA INGESTION
                         ↓
                 🧹 DATA CLEANING
                         ↓
              🔧 DATA TRANSFORMATION
                         ↓
                 🔗 DATA INTEGRATION
                         ↓
                 🗄️ DATA WAREHOUSE
                    (STAR SCHEMA)
                         ↓
                  📊 DATA ANALYSIS
                    SQL + DAX
                         ↓
                  📈 POWER BI
                    DASHBOARDS
                         ↓
                💡 MOBILITY INSIGHTS
