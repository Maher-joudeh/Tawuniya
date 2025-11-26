# Tawuniya Power BI Library

A unified, design-driven Power BI library curated by the Data Office to ensure **visual consistency**, **brand alignment**, and **efficient development workflows** across all Tawuniya dashboards.  

This repository provides:
- Official **Tawuniya Power BI Themes** (Main Brand, Data Office, and LOB-specific)
- The **ATLAS Power BI Library File** containing ready-made templates, layout structures, and formatted visuals
- A complete set of **Tawuniya assets**, **LOB logos**, and the **Desktop Grid Guide**
- A curated list of **recommended custom visuals** to extend analytical and storytelling capabilities in Power BI

---

## 🚀 How to Use the Tawuniya Power BI Library

The library supports **two approaches**:  
1) Using ready-made templates  
2) Creating your own layout using the provided components  

Choose whichever fits your workflow.

---

## 🧩 Using the Ready-Made Templates

1. **Download the ATLAS Library File**  
   This `.pbix` file includes all template pages, layout structures, typography, spacing rules, and visual styles.

2. **Open the File in Power BI Desktop**  
   Start customizing immediately.

3. **Download the Required Theme (.json)**  
   From the [Included Themes](#included-themes) section.  
   (Choose Light/Dark or the suitable line-of-business theme.)

4. **Apply the Theme**  
   Power BI Desktop → **View → Themes → Browse for themes…**  
   Select your `.json` file.

5. **Choose a Template Page**  
   Select the dashboard layout that matches your use case (Executive, Operational, Summary, KPI-driven, etc.)

6. **Customize as Needed**  
   Update titles, KPIs, visuals, colors, navigation, and filters while keeping the structure aligned with Tawuniya's design system.

7. **Connect Your Data**  
   Replace the sample data connections with your actual data sources.

8. **Remove Unused Pages**  
   Delete template pages you're not using.

9. **Publish to Power BI Service**  
   Finalize and deploy your dashboard.

---

## 🧱 Creating a New Layout 

If you prefer to build a dashboard layout different from the provided templates:

1. **Open the Visuals Section in the ATLAS Library**  
   This section contains all preformatted visuals—cards, KPIs, charts, navigation elements—already aligned with Tawuniya’s branding and visualization standards.

2. **Copy the Visuals You Need**  
   Copy any component you want and paste it onto your new blank page.

3. **Apply Any Tawuniya Theme**  
   Choose from Main Brand, Data Theme, or any LOB-specific theme for consistent color, typography, and styling.

4. **Design Your Layout**  
   Arrange visuals, adjust spacing, and structure hierarchy using the Desktop Grid Guide for precise alignment.

5. **Connect Your Data & Publish**  
   Attach your data sources, refine visuals, and publish your dashboard when ready.

---

> 💡 **Tip:** Set `Desktop Grid.svg` as your background while designing to maintain perfect spacing and alignment across your visuals.

---

## 🎨 How To Apply Custom Themes in Power BI Desktop

1. Download any `.json` theme  
2. Open your Power BI report  
3. Go to **View → Themes → Browse for themes…**  
4. Select your theme file  

➡️ Microsoft guide: https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-report-themes

---

## 🎨 Included Themes

### Main Brand Themes  
- **[Tawuniya Main Brand – Light Mode](./Tawuniya%20Main%20Brand%20-%20Light%20Mode.json)**  
  The primary corporate theme following Tawuniya’s brand colors.

### Data Office Themes  
- **[Tawuniya Data Theme – Light Mode](./Tawuniya%20Data%20Theme%20-%20Light%20Mode.json)** / **[Dark Mode](./Tawuniya%20Data%20Theme%20-%20Dark%20Mode.json)**  
  The theme used in Data Office dashboards reflecting the Data Office color palette.

### Line of Business Themes
- **General**  
  **[Light](./Line%20Of%20Business%20JSON%20Themes/General%20Theme%20-%20Light%20Mode.json)** /  
  **[Dark](./Line%20Of%20Business%20JSON%20Themes/General%20Theme%20-%20Dark%20Mode.json)**  

- **Health**  
  **[Light](./Line%20Of%20Business%20JSON%20Themes/Health%20Theme%20-%20Light%20Mode.json)** /  
  **[Dark](./Line%20Of%20Business%20JSON%20Themes/Health%20Theme%20-%20Dark%20Mode.json)**  

- **Mobility**  
  **[Light](./Line%20Of%20Business%20JSON%20Themes/Motor%20Theme%20-%20Light%20Mode.json)** /  
  **[Dark](./Line%20Of%20Business%20JSON%20Themes/Motor%20Theme%20-%20Dark%20Mode.json)**  

---

## 🗂️ Assets

This folder contains all required brand assets for dashboard development, including official Tawuniya logos, LOB logos, and the Desktop Grid Guide.

### Tawuniya LOB Logos

| Mode | General | Health | Mobility |
|------|---------|--------|----------|
| **Dark** | [General](./Assets/LOB%20Logos/Dark%20Mode/Tawuniya%20Logo%20General%20-%20Dark%20Mode.png) | [Health](./Assets/LOB%20Logos/Dark%20Mode/Tawuniya%20Logo%20Health%20-%20Dark%20Mode.png) | [Mobility](./Assets/LOB%20Logos/Dark%20Mode/Tawuniya%20Logo%20Mobility%20-%20Dark%20Mode.png) |
| **Light** | [General](./Assets/LOB%20Logos/Light%20Mode/Tawuniya%20Logo%20General%20-%20Light%20Mode.png) | [Health](./Assets/LOB%20Logos/Light%20Mode/Tawuniya%20Logo%20Health%20-%20Light%20Mode.png) | [Mobility](./Assets/LOB%20Logos/Light%20Mode/Tawuniya%20Logo%20Mobility%20-%20Light%20Mode.png) |

---

## 📏 Power BI Desktop Grid

Use this grid as a background while building dashboards to maintain spacing, alignment, and layout consistency.

![Power BI Desktop Grid](./Assets/Desktop%20Grid.svg)

**How To Use**
1. Power BI Desktop → select empty canvas  
2. **Format → Canvas background**  
3. Choose **Desktop Grid.svg**  
4. Set **Image fit: Fill**  
5. Set **Transparency: 50%**  

---

## 📌 Recommended Custom Visuals  
### [➥ Power BI Useful Custom Visuals List](./Power%20BI%20Useful%20Custom%20Visuals.md)

A curated list of powerful, free-to-use visuals that enhance:
- Storytelling  
- Visual clarity  
- Specialized analytical needs  

These visuals cover scenarios that default Power BI visuals cannot handle, and many also uplift the aesthetic and functional quality of your dashboards.

---

## License
All rights reserved for Tawuniya Insurance.  
© 2025 ATLAS Power BI Data Visualization Library. All rights reserved.
